# 📊 FluxoLab — Estúdio Visual de Fluxogramas & Arquitetura de Processos

> 🎨 **Crie, conecte, personalize e exporte fluxogramas profissionais diretamente no navegador, com suporte a formas geométricas avançadas, imagens vetoriais/rasterizadas e design limpo em modo claro.**

O **FluxoLab** é uma aplicação web de arquivo único (`HTML/CSS/JS`) que funciona como um estúdio visual dinâmico e flutuante. Desenvolvido com uma interface moderna e intuitiva, permite estruturar fluxos operacionais, mapas conceituais e arquiteturas metodológicas com alta precisão e sem necessidade de instalação.

---

## ✨ Principais Funcionalidades

* 🧩 **Biblioteca Completa de Formas:** Adicione blocos padrão de fluxograma (Início/Fim, Processo, Decisão, Documento, Dados, Nota) e formas avançadas (Círculo/Evento, Cilíndro/Banco de Dados e Contêineres de Grupo).
* 📷 **Inserção de Imagens e Ícones:** Importe arquivos externos diretamente para o quadro (`.svg`, `.ico`, `.bmp`, `.jpg`, `.jpeg`, `.png`, `.webp`), redimensione-os livremente e conecte-os com setas direcionais.
* 🔗 **Conexões Visuais Inteligentes:** Crie setas de ligação de forma intuitiva arrastando dos pontos de ancoragem azuis de um bloco até outro.
* ✍️ **Edição Direta & Flutuante:** Dê duplo clique em qualquer bloco ou seta para editar textos instantaneamente, ajustando cores de fundo e borda em painéis flutuantes.
* 🔍 **Navegação Dinâmica (Canvas Infinito):** Arraste o espaço de trabalho (*pan*), aproxime ou afaste o zoom com os botões dedicados ou com o scroll do mouse.
* 📥 **Exportação Profissional:** Exiba e salve seu trabalho em alta resolução (**PNG 2x**), **SVG vetorial** puro ou salve/carregue projetos completos em formato `.JSON`.
* 💡 **Templates Prontos:** Carregue estruturas modelo instantaneamente (como fluxos de coleta científica ou processos decisórios) para iniciar projetos em segundos.

---

## 🚀 Como Usar

1. **Execução Imediata:** Salve o código em um arquivo `fluxograma_studio.html` e abra-o em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
2. **Adicionando Elementos:** Utilize a barra superior para adicionar formas geométricas ou carregar imagens e ícones do seu computador.
3. **Movendo e Conectando:** Clique e arraste os blocos pelo canvas. Passe o mouse sobre as bordas para visualizar os pontos de ancoragem e ligá-los por setas.
4. **Salvamento:** Utilize o menu superior para exportar seu fluxograma como imagem ou salvar o progresso para edição futura.

---

## 🛠️ Arquitetura Técnica

| Camada | Tecnologia | Finalidade |
| :--- | :--- | :--- |
| 🖥️ **Interface & Estilo** | HTML5 + Tailwind CSS (Tema Claro) | Layout limpo, painéis flutuantes, responsivo e agradável à vista |
| ⚙️ **Lógica Visual** | Vanilla JavaScript (ES6+) | Manipulação de eventos de mouse, SVG dinâmico e estado reativo |
| 💾 **Persistência & Exportação** | `localStorage` + APIs de Blob / FileReader | Armazenamento local e exportação nativa em PNG, SVG e JSON |

---

## 🔮 Sugestões de Melhorias Futuras para o App

Para evoluir o **FluxoLab** em versões futuras, as seguintes melhorias podem ser implementadas:

1. **Alinhamento e Distribuição Automática:**
   * Ferramentas de alinhamento em grade (alinhar à esquerda, centralizar, distribuir espaçamento vertical/horizontal igualitário entre múltiplos blocos selecionados).
2. **Seleção Múltipla e Agrupamento:**
   * Capacidade de selecionar vários blocos de uma vez (clique e arraste em área retangular / *box selection*) para movê-los ou estilizá-los em lote.
3. **Conectores Avançados (Roteamento de Setas):**
   * Suporte a setas ortogonais/em ângulo reto (linhas que fazem curvas de 90 graus automaticamente) para evitar cruzamentos confusos sobre os blocos.
4. **Histórico Completo (Desfazer / Refazer - Ctrl+Z / Ctrl+Y):**
   * Implementação de uma pilha de comandos (*Undo/Redo*) para garantir total segurança contra edições acidentais no canvas.
5. **Biblioteca de Ícones Integrada:**
   * Um painel lateral embutido com ícones vetoriais prontos (FontAwesome ou Lucide) para inserção rápida sem depender exclusivamente de arquivos locais.
6. **Colaboração em Tempo Real:**
   * Integração opcional com WebSockets ou Firebase para permitir que múltiplos usuários editem o mesmo fluxograma simultaneamente.