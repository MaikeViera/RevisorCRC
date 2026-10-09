# RevisorCRC / AcervoScan

Leitura assistida por inteligência artificial e revisão de documentos manuscritos de registro civil.

**Status:** finalizado, conforme informado pelo autor.

## Sobre o projeto

Ferramenta que combina processamento de imagens, extração de informações com APIs de IA e revisão humana para organizar dados de documentos do acervo cartorário.

## Funcionalidades

- Pré-processamento de imagens com OpenCV: correção de inclinação, contraste, binarização e redimensionamento.
- Leitura assistida por IA de documentos manuscritos de nascimento, casamento e óbito.
- Revisão, correção e aprovação dos dados extraídos.
- Edição de datas em lote e identificação de caracteres suspeitos em nomes.
- Persistência dos dados em JSON.
- Exportação de XML para a Central de Informações do Registro Civil (CRC).

## Tecnologias

C# · .NET · WPF · Python · OpenCV · APIs de IA · JSON · XML.

## Funcionamento

Imagens dos documentos → pré-processamento → extração assistida por IA → revisão humana → exportação.

A leitura por IA depende do provedor configurado e de conexão de rede. Os resultados extraídos devem ser revisados antes da utilização.

## Disponibilidade

Este repositório apresenta o projeto. Código-fonte, instaladores e demonstração não estão incluídos nesta versão de apresentação.

## Autor

[MaikeViera](https://github.com/MaikeViera) — auxiliar de cartório, desenvolvedor e graduando em Sistemas de Informação na Universidade Federal do Amazonas (UFAM).

