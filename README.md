# Painel da Cozinha para iPad mini 1

Dashboard leve, projetado para Safari no iOS 9.3.5.

## Conteúdo
- Hora e data
- Temperatura atual
- Sensação térmica
- Umidade
- Velocidade do vento
- Previsão para 5 dias
- Atualização meteorológica a cada 30 minutos

## Local configurado
São Pedro da Aldeia, Rio de Janeiro.

## Publicação recomendada no GitHub Pages
1. Crie um repositório no GitHub, por exemplo: `ipad-kitchen-dashboard`.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Abra `Settings` > `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/root`.
6. Aguarde a publicação e abra o endereço fornecido pelo GitHub no Safari do iPad.

## Colocar na tela inicial
No Safari:
1. Toque no botão de compartilhamento.
2. Escolha `Adicionar à Tela de Início`.
3. Abra o novo ícone para usar como painel.

## Ajustes do iPad
- Ajustes > Geral > Bloqueio Automático > Nunca
- Brilho entre 35% e 50%
- Manter conectado a um carregador confiável
- Usar Acesso Guiado para impedir a saída acidental do painel

## Alterar a cidade
Edite estas linhas no arquivo `index.html`:
- `LATITUDE`
- `LONGITUDE`
- Nome da cidade exibido na seção `.place`
