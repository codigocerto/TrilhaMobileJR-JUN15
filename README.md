![Código Certo Coders](https://utfs.io/f/3b2340e8-5523-4aca-a549-0688fd07450e-j4edu.jfif)

# 📚 Trilha Inicial Mobile Jr
Este projeto tem como objetivo principal desenvolver um aplicativo de lista de tarefas simples, que permita aos usuários adicionar, visualizar e marcar tarefas como concluídas. Este projeto ajudará a avaliar o conhecimento básico em desenvolvimento mobile usando React Native, Flutter, ou Kotlin.

---

### Requisitos Funcionais

1. **Tela Inicial:**
   - Deve exibir uma lista de tarefas adicionadas.
   - Cada tarefa deve ter um título e uma opção para marcar como concluída.
   - Exibir tarefas concluídas em uma seção separada ou com uma formatação diferente.

2. **Adicionar Tarefa:**
   - Campo de entrada para o título da tarefa.
   - Botão para adicionar a tarefa à lista.

3. **Marcar Tarefa como Concluída:**
   - Cada tarefa deve ter um botão ou checkbox para marcar como concluída.

4. **Persistência de Dados:**
   - Armazenar as tarefas localmente no dispositivo para que permaneçam após fechar e reabrir o aplicativo.

---

### Requisitos Técnicos

#### React Native

**Tecnologias Sugeridas:**
- React Native
- AsyncStorage para persistência de dados
- React Navigation para navegação

**Estrutura do Projeto:**

1. **Criar um novo projeto React Native:**
   ```bash
   npx react-native init TaskListApp
   cd TaskListApp
   ```

2. **Instalar dependências:**
   ```bash
   npm install @react-navigation/native @react-navigation/stack
   npm install @react-native-async-storage/async-storage
   ```

3. **Implementar componentes principais:**
   - **Tela Inicial (HomeScreen):** Exibir a lista de tarefas e botão para adicionar novas tarefas.
   - **Componente de Tarefa (TaskItem):** Exibir título da tarefa e opção para marcar como concluída.
   - **Persistência (AsyncStorage):** Armazenar e recuperar tarefas.

#### Flutter

**Tecnologias Sugeridas:**
- Flutter
- Provider ou Riverpod para gerenciamento de estado
- SharedPreferences para persistência de dados

**Estrutura do Projeto:**

1. **Criar um novo projeto Flutter:**
   ```bash
   flutter create task_list_app
   cd task_list_app
   ```

2. **Adicionar dependências no `pubspec.yaml`:**
   ```yaml
   dependencies:
     flutter:
       sdk: flutter
     provider: ^5.0.0
     shared_preferences: ^2.0.6
   ```

3. **Implementar widgets principais:**
   - **Tela Inicial (HomeScreen):** Exibir a lista de tarefas e botão para adicionar novas tarefas.
   - **Widget de Tarefa (TaskItem):** Exibir título da tarefa e opção para marcar como concluída.
   - **Persistência (SharedPreferences):** Armazenar e recuperar tarefas.

#### Kotlin (Android)

**Tecnologias Sugeridas:**
- Android Studio
- RecyclerView para lista de tarefas
- Room Database para persistência de dados

**Estrutura do Projeto:**

1. **Criar um novo projeto Android no Android Studio:**
   - Nome do projeto: TaskListApp
   - Linguagem: Kotlin

2. **Configurar dependências no `build.gradle`:**
   ```groovy
   dependencies {
       implementation "androidx.recyclerview:recyclerview:1.2.1"
       implementation "androidx.room:room-runtime:2.3.0"
       kapt "androidx.room:room-compiler:2.3.0"
   }
   ```

3. **Implementar componentes principais:**
   - **Tela Inicial (MainActivity):** Exibir a lista de tarefas e botão para adicionar novas tarefas.
   - **Adapter de Tarefa (TaskAdapter):** Exibir título da tarefa e opção para marcar como concluída.
   - **Persistência (Room Database):** Armazenar e recuperar tarefas.

---

### Critérios de Avaliação

1. **Funcionalidade:**
   - O aplicativo atende aos requisitos funcionais?
   - É possível adicionar, visualizar e marcar tarefas como concluídas?

2. **Qualidade do Código:**
   - O código é limpo e bem organizado?
   - As práticas recomendadas de codificação foram seguidas?

3. **Interface do Usuário:**
   - A interface do usuário é intuitiva e fácil de usar?
   - O design é responsivo e funciona bem em diferentes tamanhos de tela?

4. **Persistência de Dados:**
   - As tarefas são armazenadas corretamente e recuperadas após o fechamento do aplicativo?

5. **Documentação:**
   - O projeto inclui documentação sobre como configurar e executar o aplicativo?

---

### Entrega do Projeto

1. **Repositório GitHub:**
   - Crie um repositório no GitHub e adicione o código do projeto.
   - Inclua um arquivo `README.md` com instruções de configuração e execução.

2. **Demonstração em Vídeo:**
   - Grave um vídeo curto (2-3 minutos) demonstrando as funcionalidades do aplicativo.
   - Explique brevemente a estrutura do código e as tecnologias utilizadas.

3. **Envio:**
   - Envie o link do repositório GitHub e do vídeo de demonstração para avaliação.

---

Este desafio permitirá avaliar seu conhecimento básico em desenvolvimento mobile e sua capacidade de implementar um aplicativo funcional. Estamos ansiosos para ver sua criatividade e habilidades em ação! Boa sorte!

### Dicas para Abordar o Projeto 🌟
- **Crie um Fork desse Repositório.**
- **Foco nos Detalhes:** Certifique-se de que cada funcionalidade é testada minuciosamente.
- **Documentação Clara:** Mantenha sua documentação clara e organizada para facilitar a leitura e a compreensão.
- **Teste em Diferentes Cenários:** Teste o site em diferentes navegadores e dispositivos para garantir a robustez.

### Não Queremos 🚫
- Descobrir que o candidato não foi quem realizou o teste.
- Ver commits grandes sem muita explicação nas mensagens no repositório.
- Entregas padrão ou cópias de outros projetos. Buscamos originalidade e autenticidade em cada contribuição.

### Prazo ⏳
A data máxima para entrega das trilhas foi removida, permitindo que as pessoas entreguem conforme sua disponibilidade. No entanto, ainda é necessário concluir a trilha com sucesso para ser inserido em uma equipe.

### Instruções de Entrega: 📬
Após finalizar o projeto, preencha o [Formulário](https://forms.gle/Nmyjwna23VW9rM7m9):  

---

### Desafio da Inovação 🚀
Achou esse projeto inicial simples? Eleve ainda mais! Estamos em busca de mentes inovadoras que não apenas criem, mas que também desafiem os padrões. Como você pode transformar essa estrutura inicial em algo verdadeiramente extraordinário? Demonstre o poder da sua criatividade e o impacto das suas ideias inovadoras!

---

🔗 **Mantenha-se Conectado:**
- [Discord](discord.gg/y3GHwPvsMK)
- [Website](http://www.codigocertocoders.com.br/)
- [LinkedIn](https://www.linkedin.com/company/codigocertocoders/)
  
🌐 **Contato:**
- Email: codigocertocoders@gmail.com

---

### Precisa de Ajuda?
Está com alguma dificuldade, encontrou algum problema no desafio ou tem alguma sugestão pra gente? Crie uma issue e descreva o que achar necessário.

**Construindo o amanhã, hoje.**
