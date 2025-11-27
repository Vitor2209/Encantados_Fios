🧶 Encantados_Fios — Loja de Crochê Artesanal

Bem-vindo ao repositório da Encantados_Fios, uma loja artesanal dedicada à criação de peças exclusivas de crochê feitas à mão pela artesã Vitória.
O projeto foi desenvolvido utilizando HTML, CSS e JavaScript puro, garantindo leveza, eficiência e fácil manutenção.

✨ Destaques do Projeto

Vitrine Artesanal Encantadora: layout elegante que valoriza as cores, texturas e detalhes das peças.

Front-End Puro: sem frameworks — apenas código limpo e otimizado.

Catálogo Interativo: exibição dinâmica dos produtos via JavaScript.

Pedidos via WhatsApp: atendimento direto, rápido e personalizado com a Vitória.

Design Responsivo: navegação perfeita em celulares, tablets e desktops.

🛠️ Tecnologias Utilizadas
Tecnologia	Finalidade
HTML5	Estrutura semântica e organizada do site
CSS3	Estilização, responsividade e identidade visual artesanal
JavaScript (Vanilla)	Lógica do catálogo, interação e integração com WhatsApp
🚀 Como Visualizar o Projeto

Clone o repositório:

git clone https://github.com/usuario/repositorio.git


Entre na pasta do projeto:

cd nome-do-repositorio


Abra o arquivo principal:

Clique no index.html, ou

Abra via navegador.

📁 Estrutura de Pastas
/encantados-fios
├── index.html          # Página principal da loja
├── catalogo.html       # (Opcional) Página dedicada ao catálogo
├── style.css           # Estilos e responsividade
├── script.js           # Lógica do catálogo e funcionalidades
└── assets/
    └── produtos/       # Fotos e imagens das peças de crochê

⚙️ Configuração e Manutenção
1. Editar ou adicionar novos produtos

No arquivo script.js, os produtos são armazenados em um array:

const produtosCatalogo = [
    {
        id: 7,
        nome: 'Amigurumi de Coelho',
        categoria: 'amigurumi',
        preco: 'R$ 85,00',
        imagem: './assets/produtos/coelho.jpg',
        descricao: 'Coelhinho fofo feito com linha 100% algodão.',
    }
];


Basta adicionar ou editar objetos conforme necessário.

2. Configurar o número de WhatsApp da artesã (Vitória)
const WHATSAPP_NUMBER = '55XXXXXXXXXXX'; // Número real da Vitória com DDI

3. Função de compra via WhatsApp
window.buyProduct = function(nomeProduto, preco) {
    const message = encodeURIComponent(
        `Olá! Tenho interesse no item "${nomeProduto}" (${preco}) que vi na Encantados_Fios.`
    );
    window.open(`https://wa.me/${WHATSAPP_NUMBER}?text=${message}`, '_blank');
};

💖 Feito com Carinho por Vitória

Cada peça da Encantados_Fios carrega o talento e o amor de Vitória, que transforma fios e agulhas em arte.
O objetivo desta loja é trazer aconchego, beleza e originalidade para cada cliente que escolher uma de suas criações.

