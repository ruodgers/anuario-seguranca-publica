# Anuário de Segurança Pública do Amazonas 2026

Este repositório contém a estrutura e o código-fonte do componente de visualização de dados do Anuário de Segurança Pública do Amazonas 2026. O projeto consiste em uma interface interativa para a disseminação de indicadores criminais e documentos oficiais.

## Desenvolvimento

**Responsável:** Roger Almeida
**Instituição:** Centro Integrado de Estatística de Segurança Pública (CIESP)
**Organização:** Secretaria de Estado de Segurança Pública do Amazonas (SSP/AM)

## Estrutura do Projeto

Abaixo, a descrição da organização dos diretórios e arquivos na raiz do projeto conforme a árvore de arquivos:

* **assets/**: Diretório principal de recursos estáticos.
    * **docs/**: Armazena os documentos oficiais em formato PDF (Relatórios e Infográficos).
    * **images/**: Contém as imagens dos infográficos utilizadas no carrossel.
    * **maps/**: Destinado a arquivos de cartografia e camadas de análise espacial.
    * **table/**: Reservado para bases de dados brutas e planilhas em formato Excel.
* **index.html**: Arquivo principal contendo a estrutura da interface, estilização CSS e lógica do carrossel Swiper.js.
* **README.md**: Documentação técnica do repositório.

## Especificações Técnicas

O projeto utiliza as seguintes tecnologias para garantir performance e compatibilidade:

1. **Frontend**: HTML5, CSS3 e JavaScript (ES6+).
2. **Biblioteca de Terceiros**: Swiper.js via CDN para manipulação de slides.
3. **Tipografia**: Família de fontes Roboto via Google Fonts.
4. **Hospedagem de Ativos**: Os arquivos de mídia e documentos são servidos via GitHub Raw para garantir acesso direto e integridade nos links de download.

## Procedimento para Atualização de Dados

Para atualizar os arquivos sem a necessidade de alterar a estrutura de links no código:

1. Substitua o arquivo desejado no diretório correspondente dentro da pasta `assets/`.
2. Mantenha a nomenclatura original dos arquivos para preservar as referências do `index.html`.
3. Em caso de persistência de versões antigas por cache de navegador, utilize o parâmetro de versão no código (ex: `caminho_do_arquivo.png?v=2`).

## Notas de Direitos

O conteúdo e os dados presentes neste repositório são de caráter institucional e governamental, vinculados às diretrizes de transparência da SSP/AM.
