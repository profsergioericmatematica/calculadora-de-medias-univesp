# Simulador de Médias UNIVESP 🎓🚀

Uma ferramenta web interativa e responsiva desenvolvida para auxiliar estudantes da Universidade Virtual do Estado de São Paulo (UNIVESP) no cálculo de suas médias acadêmicas. O sistema abrange as regras de avaliação para disciplinas regulares, Trabalho de Conclusão de Curso (TCC) e Projeto Integrador (PI).

## ✨ Funcionalidades

* **Calculadora de Disciplinas (Regular):**
  * Cálculo ponderado das atividades do AVA (Semanas 1 a 7) com seus respectivos pesos (8%, 12%, 17%).
  * Composição com a nota da Prova Regular (60%).
  * Alerta inteligente de Exame Final: calcula automaticamente quanto o aluno precisa tirar no exame para atingir a média 5.0.
* **Calculadora de TCC:**
  * Divisão por entregas (15% para a 1ª e 2ª entregas) e avaliação da banca (70% distribuídos entre dois avaliadores).
* **Calculadora de Projeto Integrador (PI):**
  * Cálculo baseado nas 5 avaliações do PI (Plano de Ação, Relatório Parcial, Relatório Final, Ficha/Vídeo e Avaliação Colaborativa).
* **Feedback Interativo:**
  * Sistema de cores dinâmico (Verde para aprovação, Amarelo para exame, Vermelho para reprovação).
  * Celebração de aprovação com animação de fogos de artifício na tela (com opacidade ajustada) e som de explosão gerado nativamente via Web Audio API.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível.
* **CSS3:** Estilização responsiva, variáveis de cor, animações (`@keyframes`) e design moderno em formato de "cards".
* **JavaScript (Vanilla):** Lógica matemática de cálculo, manipulação do DOM e controle do sintetizador de áudio.
* **Web Audio API:** Geração nativa de efeitos sonoros sem necessidade de arquivos `.mp3` externos.

## 🚀 Como Executar o Projeto

O projeto não possui dependências externas ou necessidade de servidor. Para utilizá-lo:

1. Faça o download ou clone este repositório.
2. Dê um duplo clique no arquivo `index.html`.
3. O simulador será aberto automaticamente no seu navegador padrão.

## 👤 Autor

Desenvolvido por **Sergio Eric Reis de Oliveira** Instagram: [@prof.sergio.eric.matematica](https://www.instagram.com/prof.sergio.eric.matematica)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
