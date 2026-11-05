# Folha — leitor e conversor de documentos

O Folha reúne leitura de PDF, visualização de documentos Word e conversão entre PDF e Word. Também oferece resumo e tradução com IA local.

## Recursos

- **Leitor de PDF:** navegue pelas páginas, ajuste o zoom e pesquise palavras no documento.
- **Copiar trechos:** selecione o texto com o mouse e copie com `Ctrl+C` ou pelo botão **Copiar seleção**. PDFs compostos apenas por imagens precisam de OCR para que o texto possa ser selecionado.
- **Visualização de Word:** abra arquivos DOCX página por página e feche a visualização quando quiser.
- **PDF para Word:** o Folha reconhece automaticamente páginas escaneadas durante a conversão. A imagem original é preservada e o texto reconhecido é incluído para edição.
- **Word para PDF:** converta arquivos DOCX para PDF usando o mecanismo de conversão incluído no instalador.
- **Resumo:** gere um resumo com IA local ou use a opção rápida sem IA. O resumo fica separado do documento original e pode ser baixado em TXT, Word ou PDF.
- **Tradução:** escolha um idioma, compare a tradução com a página original e copie ou baixe o resultado em TXT, Word ou PDF.

## Como baixar e instalar

1. Acesse a seção [Releases](https://github.com/Sr-PRESENTINHO/folha-leitor-pdf/releases).
2. Baixe `Folha-Instalador.exe`.
3. Abra o instalador e siga as instruções na tela.

O instalador inclui os componentes de conversão, OCR e o modelo de IA local.

## Requisitos

- Windows.
- Internet para carregar as ferramentas usadas pelo aplicativo.
- Para usar a IA local, é necessário um aparelho compatível com WebGPU. Na primeira utilização, o preparo do modelo pode levar mais tempo.

## Privacidade

A IA processa o texto no próprio aparelho. O conteúdo dos documentos não é enviado a um serviço externo de IA. O aplicativo carrega pela internet algumas ferramentas necessárias para leitura e conversão.

## Limitações

- A IA pode cometer erros, deixar partes sem traduzir ou resumir de forma incompleta. Revise os resultados antes de usá-los.
- A qualidade do OCR depende da nitidez e da organização das páginas escaneadas.
- A conversão pode apresentar diferenças de layout quando o documento usa fontes ou formatações que não estão disponíveis no computador.
- O texto de PDFs escaneados só pode ser selecionado depois de reconhecido por OCR.
