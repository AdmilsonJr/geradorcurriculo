# 📄 Gerador de Currículo PRO

Uma ferramenta web profissional, autônoma e de alta performance para criação de currículos. Construída com a filosofia **"Single-File"** (Arquivo Único), tudo o que você precisa está contido em um único arquivo HTML. Sem necessidade de banco de dados, servidores, Node.js ou instalações complexas.

![Status: Pronto para uso](https://img.shields.io/badge/Status-Pronto_para_uso-success)
![Tecnologia: Vanilla JS](https://img.shields.io/badge/Tech-Vanilla_JS_%7C_HTML_%7C_CSS-blue)
![Arquitetura: Single File](https://img.shields.io/badge/Arch-Single_File-orange)

## ✨ Funcionalidades

- **Arquitetura Single-File:** Interface, lógica e estilo em um só lugar. Perfeito para uso offline e envios rápidos.
- **Live Preview:** Veja o resultado final em tempo real no formato folha A4 enquanto digita.
- **Auto-Save:** Seus dados e seu progresso são salvos automaticamente no navegador (`LocalStorage`).
- **Exportação em PDF:** Geração de arquivos PDF em alta resolução (Client-Side) utilizando motores poderosos.
- **Design System Inteligente:** Três temas exclusivos e dinâmicos:
  - **Clássico:** Foco em tipografia seriada, limpo e elegante.
  - **Moderno:** Assimetria, hierarquia forte e contraste.
  - **Executivo:** Estética brutalista, direto ao ponto e focado em alto impacto.
- **Gestão de Imagens:** Upload com compressão client-side (via `<canvas>`) para evitar limites de cota de armazenamento no navegador.

## 🚀 Como Usar

Não requer nenhum tipo de instalação ou terminal.

1. Baixe os arquivos do projeto.
2. Dê um duplo clique no arquivo `index.html` para abri-lo no seu navegador favorito.
3. Preencha seus dados na barra lateral escura.
4. Escolha seu modelo favorito.
5. Quando terminar, clique no botão **Exportar PDF**.

## 🎨 Como Personalizar

O código foi feito para ser facilmente modificável. Para personalizar as cores ou as fontes base, abra o arquivo `index.html` em um editor de texto ou código (como o VS Code):

### Cores
Busque pelo bloco `:root` no topo da seção `<style>`.
Para alterar a cor de destaque principal (Verde Esmeralda), mude o valor Hexadecimal:
```css
:root {
  --primary: #10b981; /* Mude isto para a sua cor favorita */
  --primary-hover: #059669;
}
```

### Fontes
O sistema utiliza as fontes **DM Sans** e **Playfair Display**. Caso queira mudá-las:
1. Pegue o link de importação de uma nova fonte no Google Fonts.
2. Substitua as tags `<link>` no cabeçalho do arquivo HTML.
3. Altere as variáveis `--font-sans` ou `--font-serif` no bloco `:root`.

## 🛠️ Tecnologias e Bibliotecas

- **HTML5 & CSS3** (Utilizando CSS Variables e Flexbox/Grid nativos)
- **Vanilla JavaScript** (Sem React, Vue, ou pacotes npm necessários)
- **html2canvas** (via CDN): Para rasterizar a interface web em uma imagem de alta qualidade.
- **jsPDF** (via CDN): Para diagramar a imagem gerada e convertê-la em um documento `.pdf` padrão.

## 🤝 Contribuições

Sinta-se à vontade para realizar "forks", modificar para uso próprio ou sugerir novas funcionalidades! Todo o projeto é mantido focado em simplicidade, privacidade (nenhum dado do usuário vai para a internet) e velocidade.
