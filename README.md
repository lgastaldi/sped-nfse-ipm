# sped-nfse-ipm

Api para comunicação com webservices do Modelo IPM

## ALPHA TESTES (não foram feitos testes reais até o momento)

[![Latest Stable Version][ico-stable]][link-packagist]
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Latest Version on Packagist][ico-version]][link-packagist]
[![License][ico-license]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]

[![Issues][ico-issues]][link-issues]
[![Forks][ico-forks]][link-forks]
[![Stars][ico-stars]][link-stars]

Este pacote é aderente com os [PSR-1], [PSR-2] e [PSR-4]. Se você observar negligências de conformidade, por favor envie um patch via pull request.

[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[PSR-2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[PSR-4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md

Não deixe de se cadastrar no [grupo de discussão do NFePHP](http://groups.google.com/group/nfephp) para acompanhar o desenvolvimento e participar das discussões e tirar duvidas!

## Dependências

- PHP >= 7.1
- ext-curl
- ext-soap
- ext-zlib
- ext-dom
- ext-openssl
- ext-json
- ext-simplexml
- ext-libxml

### Outras Libs

- nfephp-org/sped-common
- justinrainbow/json-schema

### Municipos Atendidos pelo modelo IPM

Os dados cadastrais dos municipios estão em [storage/municipios_ipm.json](storage/municipios_ipm.json)

- Arapongas - PR
- Campo Largo - PR
- Castro - PR 
- Campo Mourão - PR
- Colombo - PR
- Enéas Marques - PR
- Guaíra - PR
- Janiópolis - PR
- Mamborê - PR
- Marechal Candido Rondon - PR
- Maripa - PR
- Mercedes - PR
- Nova Cantu - PR
- Paranaguá - PR
- Pinhais - PR
- Santa Helena - PR
- Telêmaco Borba - PR
- Terra Boa - PR
- Terra Roxa - PR
- Tibagi - PR
- Agrolândia - SC
- Apiúna - SC
- Araquari - SC
- Ascurra - SC
- Aurora  - SC
- Balneário Barra do Sul - SC
- Balneário Piçarras - SC
- Barra Velha - SC
- Benedito Novo - SC
- Biguaçu - SC
- Brusque - SC
- Concórdia - SC
- Doutor Pedrinho - SC
- Garuva - SC
- Guabiruba - SC
- Guaramirim - SC
- Ibirama - SC
- Indaial - SC
- Iporã do Oeste - SC
- Itapoá - SC
- Ituporanga - SC
- José Boiteux - SC
- Laurentino - SC
- Lontras - SC
- Massaranduba - SC
- Ouro - SC
- Palhoça - SC
- Pomerode - SC
- Presidente Getúlio - SC
- Rio das Antas - SC
- Rio do Oeste - SC
- Rio dos Cedros - SC
- Rio do Sul - SC
- Roderio - SC
- Salete - SC
- São Francisco do Sul - SC
- Taió - SC
- Timbó - SC
- Três Barras - SC
- Videira - SC
- Vitor Meireles - SC
- Witmarsum - SC
- Candelária - RS
- Estrela - RS
- Estrela Velha - RS
- Gravataí - RS
- Igrejinha - RS
- Panambi - RS
- Parobé - RS
- Santa Rosa - RS 
- Sobradinho - RS


## Contribuindo
Este é um projeto totalmente *OpenSource*, para usa-lo e modifica-lo você não paga absolutamente nada. Porém para continuarmos a mante-lo é necessário qua alguma contribuição seja feita, seja auxiliando na codificação, na documentação ou na realização de testes e identificação de falhas e BUGs.

**Este pacote esta listado no [Packgist](https://packagist.org/) foi desenvolvido para uso do [Composer](https://getcomposer.org/), portanto não será explicitada nenhuma alternativa de instalação.**

*Durante a fase de desenvolvimento e testes este pacote deve ser instalado com:*
```bash
composer require nfephp-org/sped-nfse-ipm:dev-master
```

*Ou ainda,*
```bash
composer require nfephp-org/sped-nfse-ipm:dev-master --prefer-dist
```

*Ou ainda alterando o composer.json do seu aplicativo inserindo:*
```json
"require": {
    "nfephp-org/sped-nfse-ipm" : "dev-master"
}
```

> NOTA: Ao utilizar este pacote ainda na fase de desenvolvimento não se esqueça de alterar o composer.json da sua aplicação para aceitar pacotes em desenvolvimento, alterando a propriedade "minimum-stability" de "stable" para "dev".
> ```json
> "minimum-stability": "dev",
> "prefer-stable": true
> ```

*Após os stable realeases estarem disponíveis, este pacote poderá ser instalado com:*
```bash
composer require nfephp-org/sped-nfse-ipm
```
Ou ainda alterando o composer.json do seu aplicativo inserindo:
```json
"require": {
    "nfephp-org/sped-sped-nfse-ipm" : "^1.0"
}
```

## Forma de uso
vide a pasta *Examples*

## Log de mudanças e versões
Acompanhe o [CHANGELOG](CHANGELOG.md) para maiores informações sobre as alterações recentes.

## Testing

Todos os testes são desenvolvidos para operar com o PHPUNIT

## Security

Caso você encontre algum problema relativo a segurança, por favor envie um email diretamente aos mantenedores do pacote ao invés de abrir um ISSUE.

## Credits

Roberto L. Machado (owner and developer)

## License

Este pacote está diponibilizado sob LGPLv3 ou MIT License (MIT). Leia  [Arquivo de Licença](LICENSE.md) para maiores informações.


[ico-stable]: https://poser.pugx.org/nfephp-org/sped-nfse-ipm/version
[ico-stars]: https://img.shields.io/github/stars/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-forks]: https://img.shields.io/github/forks/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-issues]: https://img.shields.io/github/issues/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/nfephp-org/sped-nfse-ipm/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-version]: https://img.shields.io/packagist/v/nfephp-org/sped-nfse-ipm.svg?style=flat-square
[ico-license]: https://poser.pugx.org/nfephp-org/nfephp/license.svg?style=flat-square
[ico-gitter]: https://img.shields.io/badge/GITTER-4%20users%20online-green.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/nfephp-org/sped-nfse-ipm
[link-travis]: https://travis-ci.org/nfephp-org/sped-nfse-ipm
[link-scrutinizer]: https://scrutinizer-ci.com/g/nfephp-org/sped-nfse-ipm/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/nfephp-org/sped-nfse-ipm
[link-downloads]: https://packagist.org/packages/nfephp-org/sped-nfse-ipm
[link-author]: https://github.com/nfephp-org
[link-issues]: https://github.com/nfephp-org/sped-nfse-ipm/issues
[link-forks]: https://github.com/nfephp-org/sped-nfse-ipm/network
[link-stars]: https://github.com/nfephp-org/sped-nfse-ipm/stargazers
[link-gitter]: https://gitter.im/nfephp-org/sped-nfse-ipm?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge