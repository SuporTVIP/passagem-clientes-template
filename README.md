# Bilhete de Embarque Digital - GOL

Um documento HTML profissional e responsivo para bilhetes de embarque, otimizado para visualização web, captura de tela e hospedagem no Google Drive.

## 📋 Conteúdo do Projeto

O bilhete inclui as seguintes seções:

- **Informações do Voo**: Aeroportos de origem e destino, horários, duração do voo, número do voo e data
- **Informações dos Passageiros**: Nomes dos passageiros e números de assento
- **Regras de Bagagem**: Infográfico visual com dimensões e pesos permitidos para bagagem de mão e despachada
- **Instruções de Embarque**: 6 passos essenciais com ícones visuais
- **Checklist de Embarque**: Infográfico com 5 pontos principais para o passageiro
- **Informações Importantes**: Avisos sobre proibições, líquidos, eletrônicos e políticas de alteração

## 🎨 Características Visuais

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Cores GOL**: Laranja (#FF6B35) e branco, seguindo a identidade visual da companhia
- **Tipografia Clara**: Fácil de ler em qualquer dispositivo
- **Imagens Integradas**: Infográficos profissionais de bagagem e checklist
- **Otimizado para Impressão**: CSS específico para impressão em PDF

## 📁 Arquivos do Projeto

```
boarding-pass-project/
├── index.html                    # Arquivo principal do bilhete
├── bagagem-instrucoes.png       # Infográfico de regras de bagagem
├── embarque-checklist.png       # Checklist de embarque
└── README.md                     # Este arquivo
```

## 🚀 Como Usar

### 1. Visualizar Localmente

```bash
cd /home/ubuntu/boarding-pass-project
python3 -m http.server 8000
```

Acesse `http://localhost:8000` no seu navegador.

### 2. Personalizar o Bilhete

Abra o arquivo `index.html` em um editor de texto e modifique as seguintes informações:

#### Informações do Voo
```html
<div class="airport-code">JPA</div>              <!-- Código aeroporto origem -->
<div class="airport-name">João Pessoa</div>      <!-- Nome aeroporto origem -->
<div class="airport-time">02h15</div>            <!-- Horário saída -->

<div class="airport-code">GIG</div>              <!-- Código aeroporto destino -->
<div class="airport-name">Rio de Janeiro</div>   <!-- Nome aeroporto destino -->
<div class="airport-time">05h20</div>            <!-- Horário chegada -->

<div class="detail-value">G7 2073</div>          <!-- Número do voo -->
<div class="detail-value">02/05/2026</div>       <!-- Data do voo -->
```

#### Informações dos Passageiros
```html
<div class="passenger-name">👤 Ana Paula Azevedo</div>
<div class="passenger-label">Assento: 12A</div>
```

#### Rodapé
```html
<div class="footer-text">Bilhete gerado em: 02/05/2026 às 14:30</div>
<div class="footer-text">Localizador: SRIOAA | Confirmação: G7 2073</div>
```

### 3. Exportar como Imagem

#### Opção A: Print para PDF (Recomendado)
1. Abra o bilhete no navegador
2. Pressione `Ctrl+P` (Windows/Linux) ou `Cmd+P` (Mac)
3. Selecione "Salvar como PDF"
4. Escolha as opções:
   - Margens: Nenhuma
   - Papel: A4 ou Carta
   - Escala: 100%

#### Opção B: Captura de Tela
1. Abra o bilhete no navegador
2. Use a ferramenta de captura de tela do seu sistema
3. Salve como PNG ou JPG

#### Opção C: Screenshot com Ferramentas
```bash
# Usando ferramentas como Puppeteer ou Playwright
# (requer instalação adicional)
```

### 4. Hospedagem no Google Drive

#### Método 1: Arquivo HTML Direto
1. Faça upload do arquivo `index.html` para o Google Drive
2. Clique com botão direito > "Abrir com" > "Google Drive"
3. Compartilhe o link

#### Método 2: Pasta Compartilhada
1. Crie uma pasta no Google Drive
2. Faça upload de todos os arquivos (index.html, imagens PNG)
3. Compartilhe a pasta
4. Acesse via navegador

#### Método 3: GitHub Pages (Alternativa)
1. Crie um repositório GitHub
2. Faça upload dos arquivos
3. Ative GitHub Pages nas configurações
4. Acesse via `https://seu-usuario.github.io/seu-repositorio`

## 🎯 Dicas de Personalização

### Mudar Cores
Procure por `#FF6B35` (laranja GOL) no CSS e substitua pela cor desejada:

```css
.header {
    background: linear-gradient(135deg, #FF6B35 0%, #FF8C42 100%);
}

.section-title {
    color: #FF6B35;
}
```

### Adicionar Mais Passageiros
Copie e cole um bloco de passageiro:

```html
<div class="passenger-item">
    <div class="passenger-name">👤 Nome do Passageiro</div>
    <div class="passenger-label">Assento: XYZ</div>
</div>
```

### Modificar Instruções de Embarque
Altere o conteúdo dos blocos de instrução:

```html
<div class="boarding-item">
    <div class="boarding-icon">⏰</div>
    <div class="boarding-text">
        <div class="boarding-title">Seu Título</div>
        <div class="boarding-desc">Sua descrição aqui</div>
    </div>
</div>
```

## 📱 Responsividade

O bilhete é totalmente responsivo e se adapta a:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## 🖨️ Otimização para Impressão

O CSS inclui estilos específicos para impressão:
- Remove sombras e gradientes complexos
- Mantém cores vibrantes
- Evita quebras de página indesejadas

## ⚙️ Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para hospedagem)
- Servidor HTTP simples (para visualização local)

## 📝 Informações Técnicas

- **Linguagem**: HTML5 + CSS3
- **Responsividade**: Mobile-first com media queries
- **Compatibilidade**: Todos os navegadores modernos
- **Tamanho**: ~16KB (HTML) + ~1.8MB (imagens)

## 🔒 Privacidade e Segurança

- Todos os dados são processados localmente
- Nenhuma informação é enviada para servidores externos
- Seguro para compartilhar via links públicos
- Recomenda-se usar links com expiração no Google Drive

## 📞 Suporte

Para modificações adicionais ou dúvidas sobre personalização, consulte a documentação HTML/CSS ou entre em contato com o desenvolvedor.

## 📄 Licença

Este template é fornecido como está. Sinta-se livre para modificar e usar conforme necessário.

---

**Última atualização**: 04 de Março de 2026
