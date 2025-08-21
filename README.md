# 🏛️ Architect Service - Landing Page Responsiva

👤 **Desenvolvido por:** Vinícius dos Santos Zapella

---

### 🎥 Demonstração do Projeto

![Demonstração do Projeto Architect Service]


---

### 💡 Sobre o Projeto

O desafio deste projeto foi transformar um design de alta fidelidade do Figma em uma landing page totalmente funcional e responsiva. A meta principal era alcançar uma réplica "pixel-perfect" do layout, utilizando as melhores práticas de desenvolvimento web moderno como **HTML semântico** e **CSS modular**, com uma arquitetura de estilos construída em **Mobile First**.

---

### 🔗 Links Relevantes

* **Layout Original (Figma):** [https://www.figma.com/design/YBFuYaYIRydws06EDvwZkv/Untitled?node-id=0-1&t=jdAxIBgVIpL61V8f-1](https://www.figma.com/design/YBFuYaYIRydws06EDvwZkv/Untitled?node-id=0-1&t=jdAxIBgVIpL61V8f-1)

---

### 🎯 Tecnologias e Conceitos Aplicados

* **HTML5**
    * Utilizado para criar uma estrutura de conteúdo limpa, acessível e otimizada para SEO.
* **CSS3**
    * **Metodologia Mobile First:** Garante uma base sólida e performática para a responsividade.
    * **Variáveis CSS (`:root`):** Permite um tema de cores e fontes consistente e de fácil manutenção.
    * **Flexbox & Grid:** Usados para criar alinhamentos precisos e layouts complexos de forma moderna.
    * **Unidades Relativas e `clamp()`:** Para criar uma tipografia e espaçamentos verdadeiramente fluidos.

---

### 🛠️ Estrutura de Arquivos

O projeto está organizado da seguinte forma:

📁 FRONTEND_REPLICAR_DESIGN_RESPONSIVO/
├── index.html            // Arquivo principal da estrutura da página
├── style.css             // Folha de estilos principal
├── /images/              // Pasta para todas as imagens e ícones
├── /fonts/               // Pasta para as fontes locais
└── README.md             // Documentação do projeto

---

### 🚀 Como Executar Localmente

Para visualizar o projeto em sua máquina, siga os passos abaixo:

1.  **Faça o download ou clone este repositório.**
2.  **Navegue até a pasta raiz** do projeto.
3.  **Abra o arquivo `index.html`** em qualquer navegador moderno.
4.  Redimensione a janela do navegador para observar a adaptação do layout em diferentes resoluções.

---

### ✅ Features Entregues

* **Fidelidade Visual:** Réplica fiel do design proposto no Figma.
* **Responsividade Completa:** Layout que se adapta perfeitamente de dispositivos móveis a desktops.
* **Código Limpo e Semântico:** Estrutura HTML que prioriza a acessibilidade e a clareza.
* **Manutenibilidade:** CSS organizado com variáveis globais, facilitando futuras alterações de design.

---

### 🧠 Desafios e Aprendizados

> 💪 **Maior desafio:** 'Garantir que a grade de serviços na seção "Our Services" se adaptasse de uma coluna no mobile para três colunas no desktop de forma fluida e sem quebrar o layout foi o principal desafio. Superei utilizando CSS Grid com a função `repeat(auto-fit, minmax(300px, 1fr))` para criar uma grade automática e flexível.'

> 💡 **Principal aprendizado:** 'Este projeto foi essencial para aprimorar meu uso da função `clamp()`. Entender como criar valores mínimos, preferenciais e máximos para fontes e espaçamentos mudou minha forma de pensar sobre design fluido, reduzindo a necessidade de múltiplos breakpoints.'

---

### 📌 Observações

* Este é um projeto puramente focado em Front-End estático (HTML/CSS), sem a inclusão de JavaScript. O objetivo principal foi a excelência na construção da interface e na sua capacidade de adaptação.
