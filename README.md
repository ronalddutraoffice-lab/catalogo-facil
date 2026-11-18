# Catálogo Fácil

Primeira versão de uma biblioteca móvel para consultar catálogos em PDF.

## O que já funciona
- Pesquisa por palavras em texto extraído dos catálogos.
- Filtros por marca e categoria.
- Ordenação A–Z e por marca.
- Resultados com página de origem.
- Armazenamento local dos PDFs no navegador do celular (IndexedDB), para abrir os originais depois de adicioná-los.
- Interface adaptada para celular e estrutura PWA instalável.

## Catálogos incluídos no índice inicial
9 catálogos únicos. Uma cópia duplicada do PDF Gastromaq foi identificada e não foi duplicada no índice.

## Limitações desta primeira entrega
Os PDFs originais não estão dentro deste pacote porque alguns arquivos são muito grandes (mais de 100 MB cada). O índice textual foi incluído. Para abrir os PDFs dentro do app, selecione-os em **Adicionar PDF** no próprio celular. O arquivo fica armazenado localmente nesse navegador/aparelho, não em uma conta online.

Alguns catálogos são digitalizados como imagem e não possuem texto extraível. Eles aparecem na lista, mas precisam de OCR para que os produtos possam ser pesquisados pelo nome. Nesta primeira versão, isso se aplica aos arquivos cuja extração de texto não retornou conteúdo útil.

## Publicar gratuitamente
Publique o conteúdo desta pasta em um repositório GitHub separado e conecte a um serviço de hospedagem de site estático. Não envie os PDFs grandes ao GitHub nesta etapa.
