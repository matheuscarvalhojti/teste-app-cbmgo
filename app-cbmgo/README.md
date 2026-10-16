# Avaliação preliminar CBMGO

Aplicativo estático em HTML, CSS e JavaScript, sem bibliotecas ou serviços externos. Pode ser aberto localmente em navegador ou publicado em hospedagem estática com HTTPS.

## O que está incluído

- Tabelas 1, 5, 6A–6C, 6D, 6E, 6F.1–6F.5, 6G.1–6G.3, 6H.1–6H.3, 6I.1–6I.2, 6J.1–6J.2 e 6M.1–6M.6 do Anexo A enviado.
- Tabelas 7 e 8, classificação de altura e triagem de processo administrativo.
- Resultados resumidos: para as Tabelas 6, só são mostradas marcações X com as notas correspondentes. Recomendações permanecem identificadas como recomendações; requisitos dependentes de informações ausentes não são presumidos.
- Para a Tabela 6C, os dados de área de depósito, área de garagem interna e altura dos expositores permitem aplicar as condições das notas 1, 7, 8, 9, 10 e 11 conforme o caso.
- A Tabela 6M.2 contém uma célula com “?” no material extraído, correspondente a uma célula em branco/indeterminada no PDF: o aplicativo não presume exigência ou dispensa.

## Como executar localmente

1. Extraia a pasta mantendo sua estrutura.
2. Abra `index.html` em um navegador moderno.
3. Preencha as características do local e selecione **Avaliar estabelecimento**.
4. Para salvar a avaliação, use a impressão do navegador e escolha “Salvar como PDF”.

## Publicar e ativar no site

1. Envie a pasta completa para uma hospedagem de site estático com HTTPS. Mantenha `index.html`, `css/` e `js/` nos mesmos locais.
2. No GitHub Pages, crie um repositório, envie o conteúdo mantendo nomes e subpastas e habilite Pages nas configurações do repositório. Aguarde o endereço de publicação indicado pela plataforma.
3. Abra o endereço em celular e computador. Faça uma avaliação de teste e confirme que formulário, estilos e scripts carregam.
4. Para exibir dentro de outra página, hospede o aplicativo separadamente e incorpore a URL em um `iframe` com `title` descritivo, `loading="lazy"` e `sandbox="allow-scripts"`. Confira a altura em telas pequenas.
5. Ao atualizar o site, substitua a versão completa e teste o endereço publicado novamente.

## Segurança e privacidade

O aplicativo processa os campos no próprio navegador e não necessita de login, banco de dados, chaves secretas ou integrações externas. Não acrescente senhas ou tokens ao código público; evite scripts e analytics externos sem revisão de privacidade e publique apenas em HTTPS. Não use os campos para dados pessoais ou sensíveis de clientes; considere também extensões, dispositivos compartilhados e as práticas do serviço de hospedagem.

## Aviso normativo

A saída é **exclusivamente orientativa** e não declara conformidade. As tabelas foram transcritas dos documentos enviados e devem ser cotejadas por profissional habilitado com a publicação oficial vigente, inclusive em futuras revisões normativas. A ferramenta não substitui a análise técnica do CBMGO nem a responsabilidade profissional (item 2.1.1 da NT 01/2026).
