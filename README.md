# 🐾 Pet\&Style – Site de Produtos para Pets

**Pet\&Style** é um projeto de site fictício desenvolvido com **HTML5** e **Tailwind CSS**, voltado para a exibição de produtos, depoimentos de clientes e informações de contato de um pet shop moderno e estiloso.

O layout foi pensado para ser **responsivo**, **modular** e com foco na **experiência do usuário**, utilizando componentes visuais claros, acessíveis e otimizados para dispositivos móveis.

---

## 🔧 Tecnologias Utilizadas

* HTML5
* Tailwind CSS v3
* Layout Flex/Grid Responsivo
* Sem frameworks JavaScript (apenas frontend estático)

---

## 🧱 Estrutura do Site

### 🔝 Cabeçalho (Header)

* Contém o logotipo e o nome da loja.
* Menu de navegação com links âncora para rolar suavemente até as seções: Início, Produtos, Depoimentos e Contato.
* Totalmente responsivo com `flex` adaptável a mobile e desktop.

---

### 🐶 Seção Hero (Início)

* Frase de impacto com texto grande, fonte destacada e cores da identidade visual (tons de âmbar).
* Imagem à direita que se adapta para cima no mobile.
* Apresentação da missão da marca: conforto, estilo e amor pelos pets.

---

### 🛍️ Seção de Produtos

* Grade com 4 produtos distintos:

  * Cama para pets
  * Ração personalizada
  * Acessórios fashion
  * Plano de saúde pet
* Cada item exibe: imagem, nome, descrição, preço e botão de ação.
* Estilizado com `rounded`, `shadow`, `hover` e `bg-amber-*`.

---

### 💬 Seção de Depoimentos

* Seção em grid que adapta entre 1 ou 2 colunas conforme o tamanho da tela.
* Cada depoimento é exibido em um card com:

  * Foto do cliente (circular, com sombra e borda)
  * Nome do cliente
  * Texto do depoimento
* Visual leve e moderno com `bg-gray-100` e `shadow-md`.

---

### 📞 Seção de Contato

* Bloco centralizado com formulário simples contendo:

  * Nome
  * E-mail
  * Telefone
  * Assunto
* Botão estilizado com hover.
* Ideal para clientes entrarem em contato com suporte ou enviarem pedidos.

---

### 👣 Rodapé (Footer)

* Informações de direitos autorais.
* Seção de contatos com links fictícios para redes sociais.
* Layout com `flex`, adaptável a colunas ou linhas.

---

## 📱 Responsividade

Todo o site utiliza utilitários do Tailwind CSS como `md:`, `sm:`, `flex-col`, `grid-cols`, `gap-*` e `px-*` para garantir uma experiência fluida em telas pequenas, médias e grandes.

---

## 📂 Organização de Arquivos (Exemplo)

```plaintext
/
├── index.html
├── src/
│   └── output.css       # Arquivo Tailwind compilado
├── img/
│   ├── logopetshop.png
│   ├── camapet.jpg
│   ├── racaopet.jpg
│   ├── acessoriopet.jpg
│   ├── planodesaudepet.jpg
│   └── Windows_10_Default_Profile_Picture.svg.png
```

---

## 🚀 Como usar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/pet-style.git
   ```
2. Abra `index.html` em um navegador.
3. Certifique-se de que o Tailwind foi compilado corretamente no `output.css`.

