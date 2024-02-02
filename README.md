# BOT DE RECADOS
🎈ENVIE SEUS RECADOS PARA SEU GRUPO OU CANAL VIA BOT DO TELEGRAM.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Esse é um aplicativo desenvolvido em Python utilizando a biblioteca gráfica Tkinter e a biblioteca de bot do Telegram, chamada Telebot. Este bot oferece uma interface gráfica simples e intuitiva para os usuários enviarem mensagens ou mídias para grupos ou canais no Telegram de forma rápida e eficiente.

## RECURSOS:
1. **Envio de Mensagens:**
   - O bot permite que os usuários ingressem o token do bot, o ID do grupo/canal de destino e a mensagem que desejam enviar.
   - O campo de mensagem é um widget de texto que permite a inserção de mensagens mais longas e formatadas.

2. **Envio de Mídias:**
   - Os usuários podem enviar mídias, como imagens ou vídeos, selecionando o arquivo desejado por meio de um botão de seleção de mídia.
   - Se uma mensagem de texto for inserida junto com uma mídia, a mensagem será usada como legenda para a mídia.

3. **Persistência de Configurações:**
   - O bot salva automaticamente o token do bot e o ID do grupo/canal em um arquivo de configuração (settings.json).
   - Ao reiniciar o bot, as informações salvas são carregadas nos campos correspondentes, proporcionando uma experiência contínua para o usuário.

4. **Feedback Visual:**
   - O bot fornece feedback visual por meio de caixas de mensagem informativas e de alerta.
   - Mensagens de sucesso, erros ou avisos são exibidas em caixas de diálogo pop-up.

5. **Facilidade de Uso:**
   - A interface gráfica foi projetada de forma simples e organizada, facilitando a compreensão e utilização por usuários de diferentes níveis de experiência.

## COMO USAR?
### BAIXANDO O PROJETO:
**Passo 1:** Clone o repositório para o seu sistema local.

```bash
git clone https://github.com/VILHALVA/BOT-DE-RECADOS.git
```

**Passo 2:** Navegue até o diretório do projeto.

```bash
cd BOT-DE-RECADOS
```

**Passo 3:** Descompacte o arquivo ZIP (se você baixou manualmente):

```bash
unzip BOT-DE-RECADOS.zip
```

### EXECUTANDO O EXECUTAVEL:
1. **Localize o Arquivo:** Após o download, localize o arquivo executável no seu sistema. Geralmente, os downloads são salvos na pasta "Downloads" do seu computador, mas você pode tê-lo salvo em outro local.

2. **Duplo Clique:** Para executar o arquivo, basta dar um duplo clique sobre ele. Isso abrirá o programa associado ao arquivo. Se o arquivo for um instalador, ele iniciará o processo de instalação. Se for um programa independente, ele será iniciado.

3. **Permissões de Administrador:** Dependendo do programa e das configurações do seu computador, você pode precisar de permissões de administrador para executá-lo. Se solicitado, clique com o botão direito do mouse no arquivo executável e selecione "Executar como administrador".

4. **Compatibilidade:** Certifique-se de que o executável seja compatível com a versão do seu sistema operacional. Se você estiver usando um sistema operacional Windows x64, o executável deve ser compilado para x64 para funcionar corretamente. Isso é importante porque o sistema operacional x64 não pode executar aplicativos compilados apenas para x86 (32 bits).

5. **Dependências:** Verifique se o executável depende de algum software adicional ou bibliotecas para funcionar corretamente. Às vezes, você pode precisar instalar outras ferramentas ou componentes antes de executar o executável.

6. **Configurações de Segurança:** Se o seu sistema operacional estiver configurado para bloquear a execução de aplicativos de fontes desconhecidas ou não confiáveis, você pode precisar ajustar as configurações de segurança para permitir a execução do executável.

7. **Atualizações e Patches:** Por fim, verifique se há atualizações ou patches para o executável, especialmente se for um software de terceiros. As atualizações podem corrigir problemas conhecidos ou adicionar novos recursos ao programa.

### EXECUTANDO O SCRIPT PYTHON:
- Para executar o código Python `(CODIGO.py)` em um PC zerado, ou seja, em um computador onde o Python não está instalado, você precisará seguir alguns passos adicionais para configurar o ambiente de execução. Aqui está um guia básico para isso:

1. **Baixe e Instale o Python:**
   - A primeira etapa é baixar o instalador do Python para o seu sistema operacional. Você pode encontrar o instalador oficial em [python.org](https://www.python.org/downloads/).
   - Se você estiver usando o Windows, certifique-se de baixar a versão adequada para o seu sistema operacional (32 bits ou 64 bits).
   - Siga as instruções do instalador para instalar o Python no seu PC.

2. **Configuração das Variáveis de Ambiente (opcional):**
   - No Windows, é uma boa prática adicionar o diretório de instalação do Python ao PATH do sistema. Isso permite que você execute comandos Python de qualquer diretório no prompt de comando.
   - Para fazer isso, após a instalação, procure "Variáveis de Ambiente" nas configurações do sistema, e adicione o caminho para o diretório de instalação do Python (normalmente algo como C:\PythonXX, onde XX é a versão do Python).

3. **Transferindo o Script para o PC:**
   - Transfira o arquivo `nome-do-arquivo.py` para o PC. Isso pode ser feito por meio de um pen drive, rede local, ou qualquer outro método de transferência de arquivo.

4. **Executando o Script:**
   - Abra um prompt de comando (no Windows, pressione `Win + R`, digite "cmd" e pressione Enter).
   - Navegue até o diretório onde o `nome-do-arquivo.py` está localizado usando o comando `cd` (por exemplo, `cd C:\Caminho\Para\O\nome-do-arquivo.py`).
   - Execute o script digitando `python nome-do-arquivo.py` e pressionando Enter.

5. **Instalando Dependências (se necessário):**
   - Se o seu script Python depende de pacotes ou módulos externos, você precisará instalá-los manualmente.
   - Use o comando `pip install nome-do-pacote` para instalar os pacotes necessários. Certifique-se de estar conectado à internet para que o pip possa baixar e instalar os pacotes.

Seguindo esses passos, você poderá executar o seu script Python em um PC zerado, mesmo sem ter o Python instalado anteriormente. Certifique-se de que todas as dependências do script estejam instaladas e que o Python esteja configurado corretamente no seu sistema. Se você não estiver familiarizado com esses passos, confira nosso [curso completo sobre o Python](https://github.com/VILHALVA/CURSO-DE-PYTHON) para obter orientações detalhadas.

## EXECUTANDO O PROJETO:
1. **Token do Bot:** Insira o token do seu bot do Telegram no campo correspondente. O qual pode ser obtido por meio do [@BotFather](https://t.me/BotFather).
2. **ID do Grupo/Canal:** Insira o ID do grupo ou canal de destino para onde deseja enviar a mensagem ou mídia. Se você não sabe qual é o `ID`, [CLIQUE AQUI](https://github.com/VILHALVA/BUSCADOR-DE-ID) para usar o nosso outro bot.
3. **Mensagem:** Digite a mensagem desejada ou deixe em branco se estiver enviando apenas mídia.
4. **Selecionar Mídia:** Clique no botão "Selecionar Mídia" para escolher um arquivo de imagem ou vídeo.
5. **Enviar:** Clique no botão "ENVIAR" para enviar a mensagem ou mídia para o grupo/canal selecionado.
6. **Limpar:** Use o botão "LIMPAR" para limpar todos os campos e iniciar uma nova mensagem.

## SAIBA MAIS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)
- [FAÇA OS NOSSOS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)


