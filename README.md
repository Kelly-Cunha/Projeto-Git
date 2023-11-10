O **Git** e o **GitHub**
são duas ferramentas relacionadas que desempenham papéis fundamentais no desenvolvimento de software colaborativo e na gestão de controle de versões.

- O **Git** permite que várias pessoas trabalhem em um projeto simultaneamente, mantendo um histórico de todas as alterações feitas. Cada desenvolvedor pode criar sua própria cópia (clone) do repositório do **Git**, trabalhar em suas mudanças em um ambiente isolado e, em seguida, mesclar (merge) essas mudanças de volta ao repositório principal. Isso torna o desenvolvimento colaborativo mais eficiente e ajuda a evitar conflitos.
- Já no **GitHub**, os repositórios **Git** são hospedados e podem ser acessados por qualquer pessoa com permissão. Desenvolvedores podem contribuir para projetos abertos enviando solicitações de pull (pull requests) para sugerir mudanças e melhorias. Além disso, o **GitHub** fornece ferramentas para rastrear problemas, gerenciar projetos, criar wikis e colaborar de maneira eficiente.

# **Criando conta no Github**

- **Acesse o site do GitHub:** Abra o seu navegador da web e acesse o site oficial do GitHub em **https://github.com/**.
- **Clique em "Sign Up”:  Na página inicial do GitHub, você verá um botão verde no canto superior direito escrito "Sign Up". Clique nele para começar o processo de registro.**
- **Preencha suas informações: Você será direcionado para uma página onde deve preencher suas informações pessoais, como seu nome de usuário, endereço de e-mail e senha. Certifique-se de escolher uma senha segura.**
- **Escolha Suas Preferências: Nesta etapa, você pode optar por receber atualizações por e-mail e selecionar suas preferências de notificação. Escolha as opções que mais lhe convêm.**
- **Complete o CAPTCHA: Prove que você não é um robô completando o CAPTCHA solicitado.**
- **Verificação de E-mail: O GitHub pode solicitar que você verifique seu endereço de e-mail. Verifique sua caixa de entrada de e-mail e siga as instruções para confirmar seu e-mail.**
- **Conclua o Registro: Após a verificação do e-mail, você será direcionado para a página inicial do GitHub com sua conta recém-criada.**

Agora, você tem uma conta no GitHub e pode começar a criar repositórios para armazenar seu código, colaborar em projetos, abrir issues e pull requests, entre outras atividades relacionadas ao desenvolvimento de software. Certifique-se de explorar a documentação e os recursos do GitHub para aproveitar ao máximo a plataforma.

# **Logando no Github localmente**

Para fazer login no GitHub localmente a partir da linha de comando do seu computador, você pode usar o comando **Git** junto com suas credenciais do **GitHub**.

- **Instale o Git (caso ainda não esteja instalado):** Se você ainda não tiver o Git instalado em seu sistema, você pode baixá-lo e instalá-lo a partir do site oficial do Git: **https://git-scm.com/downloads**.
- **Verifique a configuração do Git:** Antes de fazer login, é importante verificar se você configurou seu nome de usuário e endereço de e-mail no Git. Você pode fazer isso com os seguintes comandos, substituindo "Seu Nome" e "**[seu@email.com](mailto:seu@email.com)**" pelas suas informações reais:

```jsx
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

git config --list // Pra certificar que os dados foram salvos
```

# **Criando primeiro repositório**

Para criar o seu primeiro repositório no GitHub, siga as etapas abaixo:

- **Faça Login na sua Conta do GitHub:** Acesse **https://github.com/** e faça login na sua conta do GitHub, se ainda não estiver logado.
- **Acesse a Página Inicial do GitHub:** Após o login, você será direcionado para a sua página inicial do GitHub. Se não estiver na página inicial, clique no ícone do seu avatar no canto superior direito e selecione "Your profile" para acessar a sua página inicial.
- **Crie um Novo Repositório:** Na sua página inicial, você verá um botão verde chamado "New". Clique nele para começar a criar um novo repositório.
1. **Preencha as Informações do Repositório:** Preencha as informações necessárias para criar o seu repositório:
- **Repository name:** Escolha um nome para o seu repositório. Isso será parte do URL do seu repositório, portanto, escolha um nome significativo.
- **Description:** Adicione uma descrição opcional para o seu repositório.
- **Visibility:** Escolha se o repositório será público (visível para todos) ou privado (acesso restrito).
- **Initialize this repository with:** Você pode optar por criar um repositório vazio ou inicializá-lo com um arquivo README, um arquivo **.gitignore** e/ou uma licença. Isso depende das suas necessidades.
- **Configurações Opcionais:** Você também pode configurar outras opções, como a licença e o arquivo **.gitignore**, com base na linguagem de programação do seu projeto.
- **Clique em "Create Repository":** Após preencher todas as informações necessárias, clique no botão verde "Create Repository" na parte inferior da página.
- **Seu Repositório Foi Criado:** Parabéns! Você criou com sucesso o seu primeiro repositório no GitHub. Você será direcionado para a página do seu repositório, onde encontrará informações adicionais sobre como clonar, adicionar código e colaborar com outros desenvolvedores.

A partir deste ponto, você pode clonar o repositório para a sua máquina local, adicionar arquivos e começar a trabalhar no seu projeto. Lembre-se de configurar o Git no seu computador, se ainda não o fez, para poder fazer push e pull das alterações no seu repositório do GitHub.

# **Adicionando arquivos na área de Stage**

Para adicionar arquivos à área de stage (ou área de preparação) no Visual Studio Code (VSCode) quando você está usando um sistema de controle de versão como o Git, siga estas etapas:

- Abra o **VSCode** e navegue até o projeto que você deseja trabalhar.
- Certifique-se de que você está usando um repositório **Git**. Você pode verificar isso na parte inferior da janela do **VSCode**, onde deve mostrar a ramificação atual do **Git**. Se você não estiver usando o **Git**, você precisará inicializar um repositório **Git** no seu projeto primeiro.
- Abra o painel de controle do Git clicando no ícone de "**Source Control**" na barra lateral esquerda. Isso abrirá a exibição de controle de origem no **VSCode**.
- Na exibição de controle de origem, você verá uma lista de arquivos não rastreados (arquivos não adicionados ao **Git**) no seu projeto. Eles aparecerão como "**U**" ou "**Untracked**" ao lado deles.
- Para adicionar um arquivo à área de **stage**, clique com o botão direito do mouse no arquivo desejado na lista de arquivos não rastreados e selecione "**Stage Changes**" ou "**Stage Selected**" no menu de contexto.
- O arquivo agora será movido para a área de **stage** e aparecerá na lista de "**Changes**" na exibição de controle de origem. Os arquivos na área de stage estão prontos para serem incluídos em um commit.
- Para confirmar as alterações, insira uma mensagem de **commit** significativa na caixa de texto na parte superior da exibição de controle de origem e clique no botão de **checkmark** (**✓**) para criar o **commit**.

Lembre-se de que adicionar arquivos à área de **stage** é apenas o primeiro passo para fazer um **commit**. Você ainda precisa confirmar as alterações na área de stage criando um **commit** com uma mensagem de **commit** apropriada. Além disso, você pode usar comandos **Git** na linha de comando para realizar as mesmas ações se preferir não usar a interface gráfica do **VSCode**.

# **Fazendo o primeiro Commit**

Fazer o primeiro commit em um repositório **Git** é um passo importante, pois é quando você salva as alterações em seu projeto em um histórico de versionamento. Siga os passos abaixo para fazer o **primeiro commit**:

- Abra o **Visual Studio Code** (**VSCode**) e navegue até o projeto em que você deseja fazer o **commit**. Certifique-se de que o projeto está sob controle de versão **Git**.
- Abra o painel de controle do **Git** clicando no **ícone** "**Source Control**" na barra lateral esquerda do **VSCode**. Isso abrirá a exibição de controle de origem.
- Na exibição de controle de origem, você verá uma lista de arquivos na seção "**Changes**". Estes são os arquivos que estão na área de **stage** e estão prontos para serem incluídos no **commit**.
- Digite uma mensagem de **commit** significativa na caixa de texto na parte superior da exibição de controle de origem. A mensagem de **commit** deve resumir as alterações que você está fazendo neste **commit**. Por exemplo:

```jsx
Adicionado arquivo de configuração do projeto
```

- Clique no botão de **checkmark** (✓) na parte superior da exibição de controle de origem para criar o **commit**. Isso salva as alterações com a mensagem de **commit** que você forneceu.
- Após criar o **commit**, ele será registrado no histórico de versão do seu **repositório Git**.

Se for o seu primeiro commit em um repositório, o **Git** criará a ramificação principal (**normalmente chamada de "main" ou "master"**) automaticamente e seu **commit** será registrado nessa ramificação.

Lembre-se de que os **commits** são uma parte fundamental do controle de versão **Git** e ajudam a rastrear as alterações no seu projeto ao longo do tempo. Certifique-se de fornecer mensagens de **commit** descritivas e significativas para facilitar a compreensão das alterações realizadas em cada **commit**.

# Git push

O comando "**git push**" é usado para enviar (ou "**empurrar**") as alterações locais do seu repositório **Git** para um repositório remoto. Ele é uma das operações mais comuns no **Git** e é usado para manter sincronizados os repositórios locais e remotos. Aqui estão os passos básicos para usar o comando "**git push**":

- Certifique-se de que você está dentro do diretório do seu repositório **Git local** no **terminal**.
- Use o seguinte formato do comando **git push**:

```jsx
git push <remoto> <branch>
```

1. **<remoto>** é o nome do repositório remoto que você deseja atualizar. Isso geralmente é chamado de "**origin**" por padrão, mas você pode ter outros repositórios remotos configurados.
2. **<branch>** é o nome da ramificação que você deseja enviar para o repositório remoto.

Por exemplo, se você deseja enviar as alterações da ramificação local chamada "**main**" para o repositório remoto chamado "**origin**," você usaria o seguinte comando:

```jsx
git push origin main
```

- O **Git** solicitará suas credenciais (**nome de usuário e senha**) ou pedirá que você **autentique** de acordo com o método de autenticação configurado para o repositório remoto. Isso é necessário para garantir que você tenha permissão para enviar alterações para o **repositório** remoto.
- O **Git** enviará as alterações da ramificação local para o **repositório remoto especificado**.

É importante observar que o "**git push**" atualiza apenas as alterações na ramificação especificada no repositório remoto. Se você tiver mais de uma ramificação local que deseja enviar para o repositório remoto, você precisará executar "**git push**" para cada uma delas.

Lembre-se de que o "**git push**" é uma operação que deve ser usada com cuidado, especialmente em repositórios compartilhados. Certifique-se de **revisar** suas alterações localmente **antes** de enviá-las para o **repositório remoto** e comunique-se com a equipe para garantir que você está enviando as alterações corretas.

# **Git pull**

O comando "**git pull**" é usado para atualizar seu repositório local com as alterações mais recentes do repositório remoto. Ele combina duas operações do **Git**: "**git fetch**" e "**git merge**". Aqui está como usar o comando "**git pull**":

- Certifique-se de que você está dentro do diretório do seu repositório **Git** local no terminal.
- Use o seguinte formato do comando **git pull**:

```jsx
git pull <remoto> <branch>
```

1. **<remoto>** é o nome do repositório remoto de onde você deseja obter as atualizações. Isso geralmente é chamado de "**origin**" por padrão, mas você pode ter outros **repositórios remotos** configurados.
2. **<branch>** é o nome da ramificação remota da qual você deseja obter as atualizações.

Por exemplo, se você deseja obter as atualizações da ramificação remota chamada "**main**" do repositório remoto chamado "**origin**," você usaria o seguinte comando:

```jsx
git pull origin main
```

1. O **Git** buscará as atualizações do repositório remoto especificado.
2. Em seguida, o **Git** mesclará automaticamente as alterações buscadas na sua ramificação local. Se houver conflitos entre as alterações locais e as alterações remotas, você precisará resolver esses conflitos **antes** de poder concluir a **operação de mesclagem**.

Após executar o "**git pull**" com sucesso, seu repositório local estará atualizado com as alterações mais recentes do **repositório remoto** na ramificação especificada.

Lembre-se de que é uma boa prática usar "**git pull**" regularmente para manter seu repositório local atualizado com as alterações feitas por outros colaboradores no **repositório remoto**. Isso ajuda a evitar conflitos mais significativos no futuro.

# **Git com linha de comando**

O **Git** é amplamente utilizado através da linha de comando (**CLI**) para realizar operações de controle de versão em projetos. Aqui estão alguns dos comandos **Git** mais comuns que você pode usar na linha de comando:

- **Iniciar um Repositório:**
1. **git init**: Inicializa um novo repositório Git no diretório atual.
2. **git add .** : Adiciona todos os arquivos modificados e novos à área de stage.
3. **git commit -m "Mensagem de commit"**: Cria um novo commit com os arquivos na área de stage e uma mensagem de commit.
4. **git remote add <nome> <URL do repositório>**: Adiciona um repositório remoto ao seu projeto.
5. **git push -u origin main**: Empurra seus commits para o repositório remoto.

Esses são apenas alguns dos comandos mais comuns do **Git** que você pode usar na linha de comando.

# E**ntendendo o conceito de Branches**

O conceito de **branches** (**ramificações**) é fundamental no **Git** e em sistemas de controle de versão em geral. **Branches** permitem que você trabalhe em várias linhas de desenvolvimento independentes ao mesmo tempo, sem afetar o código em outras **branches**. Isso é especialmente útil para colaboração, experimentação e gerenciamento de versões de software.

- **O que é uma Branch**:
1. Uma branch é uma linha de desenvolvimento separada dentro de um repositório Git.
2. Ela contém uma cópia do código do projeto, permitindo que você faça alterações sem afetar o código em outras branches.
- **Por que Usar Branches:**
1. Para isolar diferentes tarefas ou recursos em desenvolvimento, tornando mais fácil para várias pessoas colaborarem no mesmo projeto sem interferências.
2. Para experimentar novos recursos ou correções de bugs sem comprometer a estabilidade do código principal (geralmente na branch principal).
3. Para facilitar a manutenção de versões do software, onde cada versão é representada por uma branch separada.
- **Branch Principal (Master ou Main):**
1. Geralmente, um repositório **Git** tem uma branch principal (geralmente chamada de "**master**" ou "**main**") que representa o estado estável do código.
2. As novas funcionalidades e correções de bugs são frequentemente desenvolvidas em **branches** separadas e, uma vez testadas e revisadas, são mescladas na **branch** principal.

- **Criando e Gerenciando Branches:**
1. Para criar uma nova branch, você pode usar o comando **git branch <nome_da_branch>**. Em seguida, você pode mudar para essa branch usando **git checkout <nome_da_branch>**.
2. Uma abordagem mais comum é criar e mudar para uma nova branch com um único comando: **git checkout -b <nome_da_branch>**.
3. Para listar todas as branches em um repositório, use **git branch**.

- **Mesclando Branches:**
1. Uma vez que você tenha feito alterações em uma **branch** e deseja incorporá-las de volta à **branch** principal ou a outra branch, você usa a operação de "**merge**".
2. O comando **git merge <nome_da_branch>** integra as alterações de uma branch em outra.
3.  Às vezes, podem ocorrer conflitos de **merge** que precisam ser resolvidos manualmente.

- **Excluindo Branches:**
1. Você pode excluir branches que não são mais necessárias usando **git branch -d <nome_da_branch>**. Tenha cuidado ao excluir branches, pois as alterações não mescladas serão perdidas.

- **Trabalho em Equipe:**
1. **Branches** são essenciais para facilitar o trabalho em equipe, pois permitem que várias pessoas trabalhem em diferentes partes do projeto sem conflitos frequentes.
2. Repositórios remotos, como **GitHub** e **GitLab**, também facilitam a colaboração por meio de **pull requests** (**solicitações de mesclagem**), onde as alterações de uma branch são revisadas antes de serem mescladas na branch principal.

Em resumo, o uso eficiente de branches no **Git** é uma prática recomendada para organizar e gerenciar o desenvolvimento de software, permitindo que você mantenha um histórico limpo, trabalhe de forma **colaborativa** e experimente novas funcionalidades com segurança.

# **Git merge**

O comando "**git merge**" é usado para mesclar as alterações de uma **branch** em outra **branch** no **Git**. Geralmente, você usa o "**git merge**" para incorporar as alterações de uma **branch** de desenvolvimento (**geralmente uma feature branch**) em uma **branch** principal (como a **branch** "**main**" ou "**master**"). Aqui estão os passos básicos para usar o "**git merge**":

- **Certifique-se de estar na branch de destino:**
1. Antes de usar o comando "**git merge**", verifique se você está na **branch** de destino (**a branch em que você deseja incorporar as alterações**). Você pode mudar para a branch de destino usando o comando "**git checkout <branch_destino>**".

```jsx
git checkout main  # Por exemplo, mude para a branch "main"
```

- **Execute o comando "git merge":**
1. Use o comando "**git merge**" seguido pelo nome da **branch** que você deseja mesclar na **branch** de destino. Por exemplo, para **mesclar** as alterações da **branch** "**feature/nova-funcionalidade**" na **branch** "**main**", você usaria o seguinte comando:

```jsx
git merge feature/nova-funcionalidade
```

Isso fará com que o **Git** tente combinar as alterações da **branch** "**feature/nova-funcionalidade**" na **branch** "**main**".

- **Resolva conflitos (se necessário):**

Se houver conflitos entre as alterações na **branch** de destino e na **branch** que você está **mesclando**, o **Git** informará que ocorreu um conflito e pausará o processo de **mesclagem**. Você precisará resolver esses conflitos manualmente, editando os arquivos conflitantes para escolher as partes apropriadas de cada conjunto de alterações.

Depois de resolver os conflitos, adicione os arquivos modificados à **área de stage** usando "**git add**" e, em seguida, continue a **mesclagem** usando "**git commit**" para criar um novo **commit** de **mesclagem**.

- **Crie um commit de mesclagem (se necessário):**

Se houver conflitos a serem resolvidos, após resolvê-los, você deve criar um novo **commit** de **mesclagem** usando "**git commit**". O **Git** automaticamente adicionará uma mensagem de **commit** padrão descrevendo a **mesclagem**.

- **Finalize a mesclagem:**

Após resolver os conflitos (**se houver**) e criar o **commit** de **mesclagem**, a **mesclagem** estará concluída.

Agora, a **branch** de destino (por exemplo, "**main**") conterá as alterações da **branch** de **origem** (por exemplo, "**feature/nova-funcionalidade**").

O "**git merge**" é uma operação fundamental para a gestão de **branches** e permite que você incorpore o trabalho de diferentes ramos de desenvolvimento em uma única linha de código. No entanto, lembre-se de que é importante realizar testes adequados após a **mesclagem** para garantir que as alterações não introduziram problemas no código.
