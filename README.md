# Landing Page - Receitas Low-Cost Portugal (€12,90)

Landing page de alta conversão para o guia **"Receitas Low-Cost Portugal: Como viver com 600€ de compras"**.

## Informações do produto (alinhadas com o checkout)

- **Nome**: Receitas Low-Cost Portugal: Como Viver...
- **Preço**: € 12,90 EUR
- **Prova social**: +1256 pessoas já compraram
- **Checkout**: https://checkout.escalepay.com/1117594
- **Entrega**: Imediata / automática após pagamento

## Características da página

- Proposta de valor clara
- Design focado no CTA (sem menu de navegação)
- Benefícios em cards
- Prova social (+1256 compradores)
- Contador de oferta especial (igual ao checkout)
- FAQ para eliminar objeções
- 100% responsiva + botão sticky no mobile
- Cores alinhadas com o checkout (verde + barra vermelha de urgência)

## Estrutura

```
landing-page/
├── index.html
├── css/style.css
├── js/main.js
├── images/
│   └── ebook-600.jpg
└── README.md
```

## Pré-visualizar

Abra o ficheiro `index.html` no navegador ou:

```bash
python -m http.server 8000
```

## Deploy no OnRender (Static Site)

1. Crie conta em [render.com](https://render.com)
2. **New +** → **Static Site**
3. Faça upload do ZIP ou conecte o repositório
4. Configurações:
   - **Build Command**: (deixe vazio)
   - **Publish Directory**: `.`  (ou `landing-page` se necessário)
5. Clique em **Create Static Site**

Pronto. O site fica online em poucos minutos.

## Checklist antes de anunciar

- [ ] Testar o link do checkout no telemóvel
- [ ] Verificar se a imagem carrega
- [ ] Confirmar o preço €12,90
- [ ] Testar no Chrome e Safari mobile
- [ ] Adicionar Pixel do Facebook se necessário (no `<head>`)

Boa conversão!
