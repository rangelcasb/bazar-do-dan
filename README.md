# 🎆 Bazar do Dan - Catálogo de Fogos de Artifício

Catálogo online interativo e responsivo para revenda de fogos de artifício em Maceió, Alagoas.

## ✨ Funcionalidades

✅ **Design Responsivo** - Funciona perfeitamente em celular, tablet e desktop  
✅ **Busca de Produtos** - Procure por nome instantaneamente  
✅ **Filtro por Preço** - Ajuste a faixa de preço desejada  
✅ **Categorias** - Organize produtos por tipo  
✅ **Carrinho de Compras** - Selecione produtos e totalize o pedido  
✅ **Integração WhatsApp** - Compartilhe produtos e faça pedidos direto  
✅ **Dark Mode** - Interface elegante em tons de preto e ouro  

## 🚀 Como Usar

1. Abra o arquivo `index.html` no seu navegador
2. Navegue pelos produtos
3. Use os filtros para encontrar o que procura
4. Clique em "Compartilhar" para enviar pelo WhatsApp
5. Clique no carrinho para fazer o pedido completo

## 📱 Número do WhatsApp

Altere o número na linha 281 do arquivo `index.html`:
```javascript
const whatsappNumber = "5582999999999";
```

Substitua pelo seu número no formato: `55` + DDD + número (sem símbolos)

## 🎨 Cores da Marca

- **Ouro Principal**: #FFD700
- **Laranja/Destaque**: #FFA500
- **Vermelho (Preços)**: #E63946
- **Fundo**: #000000 (Preto)
- **Verde WhatsApp**: #25D366

## 📦 Estrutura de Arquivos

```
bazar-do-dan/
├── index.html    (arquivo principal com código completo)
└── README.md     (este arquivo)
```

## ⚙️ Personalização

### Adicionar/Alterar Produtos

Edite a lista `products` no arquivo `index.html` (linha ~280):

```javascript
{ 
    id: 1, 
    name: "Nome do Produto", 
    unidades: "Qtd unidades", 
    preco: 9.99, 
    categoria: "Categoria",
    badge: "Opcional"
}
```

### Alterar Número do WhatsApp

Procure pela linha:
```javascript
const whatsappNumber = "5582999999999";
```

E substitua pelo seu número.

## ⚖️ Informações Legais

Lei Estadual AL nº 9.146/2024 - Proibição de fogos com estampido em Alagoas a partir de 2026.

Produtos recomendados para após 2026:
- Chuvinhas
- Mariposas
- Abelinhas
- Libélulas
- Flores visuais

## 📞 Suporte

Para dúvidas ou alterações no catálogo, entre em contato.

---

**Versão**: 1.0  
**Última atualização**: Abril 2026  
**Desenvolvido com ❤️ em Maceió, AL**
