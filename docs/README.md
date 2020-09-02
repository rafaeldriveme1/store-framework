# VTEX IO

https://vtex.io

https://lab.github.com/vtex-trainings/store-framework?overlay=register-box-overlay

#### Requisitos

- NodeJS
- Yarn

## Iniciando

#### Instalando Toolbelt

```sh
yarn global add vtex

npm i -g vtex
```

#### Para confirmar se a instalação do Toolbelt ocorreu como esperado.

```sh
vtex-v
```

## Login

#### Fazendo login

```sh
vtex login contaVTEX
```

#### Para confirmar em qual conta e workspace você está

```sh
vtex whoami
```

## Workspaces

Ambientes de trabalho protegidos que representam uma cópia bem próxima do está montado em produção, possibilitando a evolução de temas sem que nada na loja seja afetado. 

#### Ver todos os workspaces

```sh
vtex workspace -ls
```

#### Criando um workspace de desenvolvimento

https://devworkspace--appliancetheme.myvtex.com

```sh
vtex use nome-do-workspace
```

## Link

#### Rodar o projeto

```sh
vtex link --verbose
```

#### Abrir no browser

```sh
vtex browse
```

#### Deslinkar

```sh
vtex unlink
```

## Apps

#### Ver apps instalados

```sh
vtex ls
```

#### Instalar app

```sh
vtex install compracerta.store-theme
```

#### Help

```sh
vtex help
```

## Outros

#### html-to-jsx

https://transform.tools/html-to-jsx

#### CSS handles

https://vtex.io/docs/recipes/style/using-css-handles-for-store-customization/

https://homolog1--compracerta.myvtex.com/admin/cms/site-editor
