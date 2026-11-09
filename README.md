# Mundo dos Geeks

Site estático de descoberta de Rap Geek. Projeto independente, sem fins lucrativos e feito por diversão.

## Fontes de dados
- **Apple iTunes Search API:** pesquisa faixas, capas, prévias de 30 segundos e datas de lançamento. Não exige chave. A Apple informa limite aproximado de 20 chamadas por minuto; o site usa cache no navegador para reduzir chamadas.
- **Audius API:** tendências de faixas dentro do Audius. A API permite consultas públicas de leitura sem credenciais, sujeitas a limites e disponibilidade.
- **Letras:** o site apenas encaminha para pesquisas externas. Não armazena nem republica letras protegidas por direitos autorais.

## Como testar
Abra `index.html` em um navegador com internet. Para melhor compatibilidade, use uma hospedagem estática HTTPS.

## Como publicar gratuitamente com GitHub Pages
1. Entre no GitHub e crie um repositório público chamado `mundo-dos-geeks`.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
6. Aguarde a publicação. O GitHub mostrará o endereço público do site na própria página Pages.

O GitHub Pages hospeda sites estáticos em repositórios públicos no plano gratuito. O site não tem servidor, login ou banco de dados; playlists e artistas favoritos ficam salvos apenas no navegador de cada visitante.

## Limitações honestas
- “Recentemente lançadas” usa datas de lançamento encontradas no catálogo iTunes e não representa todos os lançamentos de Rap Geek.
- “Em alta” mostra tendências do Audius, não um ranking global de streams.
- A qualidade das recomendações depende de como as plataformas catalogam artistas e faixas. O mapa de artistas relacionados é uma curadoria inicial e pode ser ampliado.
- APIs públicas podem mudar, ficar indisponíveis ou impor limites. O site mostra mensagens quando isso acontece.
- Pré-visualizações de áudio só aparecem quando o catálogo fornece uma URL de prévia.

## Privacidade
Não há conta, analytics, anúncios ou coleta própria de dados. Preferências e playlist são armazenadas no `localStorage` do navegador.
