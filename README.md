# 🎯 Sorteador de Números

Um projeto prático de sorteador de números desenvolvido para exercitar lógica de programação em JavaScript, manipulação de DOM e validações de fluxo.

## 🚀 Funcionalidades

- Sorteio de múltiplos números de uma só vez.
- Definição de intervalo (número mínimo e máximo).
- **Validação de Inclusividade:** O sistema impede sorteios se a quantidade pedida for maior que o intervalo disponível.
- **Prevenção de Duplicatas:** O algoritmo garante que nenhum número seja sorteado mais de uma vez no mesmo ciclo.
- Interface Responsiva com feedback visual para botões habilitados/desabilitados.

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página.
- **CSS3** - Estilização (seguindo padrões de acessibilidade visual).
- **JavaScript (ES6+)** - Lógica de sorteio, validações e manipulação de classes.

## 📝 Como funciona a lógica?

O projeto utiliza a função `obterNumeroAleatorio` baseada no método `Math.random()`. A principal lógica de segurança reside nas **Cláusulas de Guarda** (Early Returns), que validam os inputs antes de iniciar o loop de sorteio, evitando erros de execução ou loops infinitos.

```javascript
// Exemplo da lógica de validação utilizada
if (quantidade > capacidadeDisponivel) {
    alert("Erro: Quantidade solicitada excede o intervalo!");
    return;
}

🔧 Como rodar o projeto

Faça o clone do repositório:

git clone [git@github.com:antonioelton-debug/projeto-1-sorteador-de-numeros.git](git@github.com:antonioelton-debug/projeto-1-sorteador-de-numeros.git)

Abra o arquivo index.html no seu navegador ou utilize a extensão Live Server do VS Code.

👨‍💻 Autor
Antonio Elton

QA Analyst | Software Tester

```
