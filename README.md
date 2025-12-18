# 🎮 Tic Tac Toe

Este é um projeto de Jogo da Velha moderno, desenvolvido para explorar as funcionalidades mais recentes do **React 19**. Diferente de uma implementação simples, este projeto foca na imutabilidade do estado e no rastreio de histórico de ações.

## 🚀 Demonstração
O projeto está publicado na **Vercel** e pode ser testado aqui: 
[https://tic-tac-one-psi.vercel.app/](https://tic-tac-one-psi.vercel.app/)]

## 🛠️ Tecnologias e Ferramentas
- **React 19**: Utilização de Hooks (`useState`) para gestão de estados complexos.
- **Vite**: Build tool de alta performance para um desenvolvimento ágil.
- **JavaScript (ES6+)**: Lógica de algoritmos para verificação de vencedores.
- **CSS3**: Estilização com foco em UI moderna (Glassmorphism) e responsividade.
- **ESLint**: Configurado para garantir a padronização e qualidade do código.

## 🧠 Diferenciais Técnicos
- **Time Travel (Histórico)**: O jogo armazena cada movimento num array imutável, permitindo a gestão do estado de forma previsível.
- **Persistência de Sessão**: Implementei um sistema de "Histórico de Ganhadores" que mantém o registo dos vencedores da sessão, mesmo após o tabuleiro ser reiniciado.
- **Imutabilidade**: Uso de padrões de cópia de arrays (`slice()`) para evitar mutações diretas no estado do React, seguindo as melhores práticas da biblioteca.

## 📂 Como Rodar Localmente
1. Clone o repositório:
   ```bash
   git clone [https://github.com/fernandarrocha/TicTac.git](https://github.com/fernandarrocha/TicTac.git)

## Funcionalidades

•
Jogo da velha interativo.

•
Interface simples e intuitiva.

•
Design responsivo para diferentes tamanhos de tela.
