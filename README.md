# Circuito do Jogo Snake no Logisim  

## 📌 Descrição  

Este projeto implementa o clássico jogo **Snake** utilizando a ferramenta de simulação de circuitos digitais **Logisim**. O sistema é desenvolvido com uma abordagem modular, integrando diferentes componentes que trabalham sincronizados para garantir uma experiência de jogo funcional e interativa.  

### 🏗 Estrutura do Circuito  

O circuito é dividido em diversos blocos que desempenham funções específicas, tais como:  

- **Key Control Module** – Captura os comandos do usuário e impede movimentações inválidas.  
- **Snake Moving Module** – Atualiza as coordenadas da cobra com base nos comandos e no ciclo de clock.  
- **Memory Shifter e Snake Length Counter** – Gerenciam a estrutura da cobra e seu crescimento progressivo.  
- **Display Circuit e Screen Output Module** – Processam os dados para exibição dos elementos do jogo na tela.  
- **Clock e Reset System** – Sincronizam todas as operações, garantindo transições e estados previsíveis.  

## 📸 Capturas de Tela  

Para uma melhor compreensão do funcionamento do circuito, recomenda-se incluir as seguintes imagens:  

1. **Visão Geral do Circuito** – Representação completa dos módulos e suas interconexões.  
2. **Módulo de Controle do Teclado** – Estrutura de captura e processamento de comandos.  
3. **Módulo de Movimentação da Cobra** – Detalhamento dos mecanismos de atualização das coordenadas X e Y.  
4. **Gerenciamento de Memória e Crescimento** – Ilustração do funcionamento dos registradores e contadores.  
5. **Exibição na Tela** – Como os sinais são convertidos para gerar a saída visual do jogo.  

## ⚙️ Requisitos  

Para executar o projeto, você precisará de:  

- **Logisim** (versão mais recente recomendada).  
- Arquivo `.circ` contendo o circuito digital do jogo.  
- Familiaridade com lógica digital e operações binárias pode ajudar na compreensão do projeto.  

## 🚀 Como Usar  

1. **Clone o repositório:**  
   ```sh
   git clone https://github.com/seuusuario/repo-snake-logisim.git
