# Conclave Hero Forge — Gerador de Heróis

Aplicação web estática em português, inspirada em editores de avatar tipo Picrew e fantasia de RPG. Não usa servidor, framework, build ou API externa: basta hospedar os arquivos estáticos.

## Funcionalidades implementadas

- Preview frontal em canvas com quatro bases corporais ilustradas.
- Personalização de tom de pele, escala, cabelo/penteado/cor, barba, expressão, vestuário/paleta, arma e escudo.
- Opções de fundo noturno, pergaminho ou transparente.
- Geração aleatória e reinício.
- Salvar localmente, abrir coleção, carregar e excluir personagens (localStorage do navegador).
- Exportar PNG do personagem e exportar/importar configuração JSON.
- Compartilhar configuração por URL (hash).
- Layout adaptável para desktop e celular.
- Deploy automático pelo GitHub Actions para GitHub Pages.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie **o conteúdo desta pasta** para a raiz do repositório (inclua `.github/workflows/pages.yml`).
3. Em `Settings → Pages`, selecione `GitHub Actions` como fonte (se solicitado).
4. Faça push na branch `main`. O workflow publica automaticamente.
5. A URL geralmente será `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Uso local

Abra `index.html` em um navegador moderno. Nenhuma dependência externa é carregada.


## Licença e assets

O código está sob licença MIT (consulte `LICENSE`). As quatro bases PNG foram geradas especificamente para o protótipo. O ZIP de referência enviado pelo usuário não foi incorporado ao projeto: seus assets/licença restringem o uso fora do Foundry VTT/D&D 5e. Antes de ampliar ou comercializar o projeto, revise os termos/licenças dos assets gerados.

## Limitações desta versão

Esta é uma primeira versão funcional do editor, não um Picrew completo de recortes independentes. As bases incluem roupa e rosto, e os overlays são desenhados em Canvas. Para fidelidade a um sistema modular de camadas, o próximo ciclo de assets deve criar PNGs transparentes independentes (corpo, cabeça/face, cabelo traseiro/frontal, roupa, braços, pernas, calçado, acessórios), com canvas e alinhamento padronizados.
