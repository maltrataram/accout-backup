<div align="center">
    <h1>Discord Backup</h1>
    <p>☁️ Backup and Restore your Discord Account in minutes.</p>
    <img src="https://img.shields.io/github/license/ItsChasa/Discord-Backup?style=flat">
    <img src="https://img.shields.io/github/downloads/ItsChasa/Discord-Backup/total?style=flat">
    <img src="https://img.shields.io/github/stars/ItsChasa/Discord-Backup?style=flat">
    <img src="https://img.shields.io/github/forks/ItsChasa/Discord-Backup?style=flat">
    <img src="https://sonarcloud.io/api/project_badges/measure?project=itschasa_Discord-Backup&metric=ncloc"/>
    <br>
    <img src="https://github.com/ItsChasa/Discord-Backup/blob/main/img/backup-demo.gif">
    <br>
    <p><i>⭐ star the repo pls <3</i></p>
</div>




## Disclaimer 
A automação de contas Discord, também conhecidas como self-bots, é uma violação dos Termos de Serviço e Diretrizes da Comunidade do Discord e resultará no encerramento de sua(s) conta(s). A discrição é aconselhada. Não serei responsável por suas ações. Leia sobre os [Termos de Serviço](https://discord.com/terms) e as [Diretrizes da Comunidade](https://discord.com/guidelines) do Discord aqui.


## **Features**:
### Automatic
Isso pode ser feito pelo programa:
- Servidores de backup
  - Salvar convites do servidor
- Backup do histórico de DM
  - Salve usuários que enviaram DM para você
- Backup de bate-papos em grupo
  - Salvar convites para bate-papos em grupo
- Backup de avatar, banner e biografia
  - Salva 1 arquivo .txt e 2 .gif
- Backup + restauração de pastas do servidor
  - Salva a ordem, cor e nome de suas pastas
- Relacionamentos de backup + restauração
  - Salvar amigos, amigos bloqueados, de saída e de entrada
- Backup automático na inicialização do PC
  - Na inicialização, faça backup automaticamente da sua conta Discord
- Personalização de cores
  - 12 cores diferentes para escolher
### Manual
Você terá que fazer isso sozinho:
- Restaurar servidores
  - Você terá que ingressar nos Servidores clicando em um convite no Discord
- Restaurar bate-papos em grupo
  - Você terá que participar dos bate-papos em grupo clicando em um convite no Discord
- Restaurar Avatar, Banner e Bio
  - Você terá que adicioná-los novamente através do menu Perfil do usuário


## Installation
### Using Binary EXE (Easier)
1. Baixe o zip para o seu sistema operacional desde o lançamento
2. Descompacte o conteúdo em uma pasta
3. Execute o exe

### Using Source
1. Instale [Python 3.9.10](https://www.python.org/downloads/release/python-3910/) (deve funcionar com outras versões)
2. Baixe a fonte com o botão verde `Código` e depois `Baixar ZIP`
3. Descompacte o conteúdo em uma pasta
4. Execute em seu prompt de comando:
```
pip instalar -r requisitos.txt
```
5. Execute main.py, clicando duas vezes ou com prompt de comando (maneira preferida):
```
python principal.py
```
## How to Use
1. Instale seguindo as instruções acima e execute o programa.

### Backing Up
2. Selecione a opção 1 para fazer backup de uma conta Discord.
3. Você pode procurar tokens (contas Discord) em seu PC ou inseri-los manualmente.
  - Se você não tem experiência com o Discord, recomendamos verificar se há tokens no seu PC.
  - No entanto, se você não quiser deixar o programa fazer isso ou a conta não aparecer durante a digitalização, você pode inserir o token manualmente.
4. O programa agora deve começar a fazer backup da sua conta. Isso deve levar de 1 a 10 minutos, dependendo de quantos servidores e chats em grupo você participa.
5. Assim que o programa terminar, você verá uma visão geral do backup, onde poderá ver se o backup de alguma guilda falhou. Neste ponto, o arquivo .bkup será salvo na pasta `backups`.
6. Também recomendamos que você configure o Backup Automático, selecionando a Opção 3.

### Restoring
2. Quando precisar restaurar a partir de um backup, selecione a Opção 2.
3. Selecione a opção 1: restaurar tudo.
4. Agora você pode escolher se deseja restaurar seus amigos, saída, etc. Selecione `y` para sim ou `n` para não em cada um.
5. Uma nova janela será aberta, solicitando que você selecione o arquivo .bkup. Encontre-o e selecione-o.
6. Depois de verificar as configurações, selecione `y` ou `n`.
7. Agora, você pode escolher se deseja procurar tokens ou inserir manualmente. As mesmas instruções de `3.` no backup se aplicam aqui.
8. Depois de inserir seu token, você precisa inserir um Token de Bot. Você pode obter um no Portal do Desenvolvedor Discord.
- a. Vá para https://discord.com/developers/applications
- b. Clique em `Novo aplicativo` e digite um nome aleatório.
- c. Na barra lateral, clique em `Bot`, depois em `Add Bot` e em `Yes, do it!`
- D. Clique em `Copiar` (localizado próximo a `Ver Token`). O Bot Token está agora na sua área de transferência!
9. O programa começará a restaurar sua conta. Observação: é provável que esse processo demore mais do que o backup, dependendo de quantos relacionamentos você teve.
10. Assim como no backup, você terá uma visão geral do que aconteceu durante o processo de restauração após sua conclusão.
11. Depois de ingressar em todos os servidores, você pode voltar ao programa e selecionar a Opção 2: Restaurar pastas do servidor para restaurar as pastas do servidor. Ou você pode fazer esse processo manualmente.

## Notes / FAQ:
### Restoring Servers + Group Chats + Server Folders
Por causa dos últimos recursos do Discord de usar hCaptcha para impedir que as pessoas façam bots no Discord, decidi que é melhor impedir que este programa precise de uma chave captcha.
- O programa criará um servidor com todos os convites de servidor antigos, classificados nas pastas da conta antiga.
- Você simplesmente se junta a eles, quando precisar.
- Depois de ingressar em todos os servidores, você poderá usar o módulo de restauração apenas para restaurar pastas.

### Convites para bate-papo em grupo
Os convites para bate-papo em grupo são um pouco desgastados no Discord.
- Os convites do servidor ainda estarão ativos se você sair do servidor.
- No entanto, os convites para bate-papo em grupo não funcionarão **se você sair** do bate-papo em grupo.
- Ou seja, se você sair do bate-papo em grupo após um backup e antes do término do período, não poderá entrar novamente nesse bate-papo em grupo.

### Posso fazer backup/restaurar uma conta que já esteja nomeada?
Não. Você não pode e nunca será capaz. Pare de perguntar isso.

### There's a feature I want to suggest.
Suggest it in the issues tab. I will probably add it.

### I keep getting an error, help!
Make an issue in the issue tab, or ask in the Community Servers.
