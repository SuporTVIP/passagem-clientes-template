# Variáveis de Personalização - Bilhete de Embarque

Use este arquivo como referência para personalizar rapidamente o bilhete para diferentes clientes.

## 📋 Informações do Voo

```
Aeroporto Origem (Código):    JPA
Aeroporto Origem (Nome):      João Pessoa
Horário Saída:                02h15

Aeroporto Destino (Código):   GIG
Aeroporto Destino (Nome):     Rio de Janeiro
Horário Chegada:              05h20
Duração do Voo:               3h05

Número do Voo:                G7 2073
Data do Voo:                  02/05/2026
Classe:                       Econômica
```

## 👥 Passageiros

```
Passageiro 1:
  Nome:                       Ana Paula Azevedo
  Assento:                    12A

Passageiro 2:
  Nome:                       Julison Wiber Araújo
  Assento:                    12B

Passageiro 3:
  Nome:                       Luan Felipe Albuquerque
  Assento:                    12C
```

## 📅 Informações Administrativas

```
Localizador:                  SRIOAA
Confirmação:                  G7 2073
Data de Geração:              02/05/2026
Hora de Geração:              14:30
```

## 🎨 Personalizações Visuais

### Cores
- Cor Primária (Laranja):     #FF6B35
- Cor Secundária (Laranja Claro): #FF8C42
- Cor de Fundo:               #f9f9f9
- Cor de Texto:               #333

### Fontes
- Fonte Principal:            'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- Tamanho Título:             28px
- Tamanho Subtítulo:          14px

## 📝 Instruções de Embarque (Personalizáveis)

### Instrução 1
- Ícone: ⏰
- Título: Chegada no Aeroporto
- Descrição: Chegue com 3 horas de antecedência para voos internacionais e 2 horas para voos domésticos.

### Instrução 2
- Ícone: ✓
- Título: Check-in
- Descrição: O check-in encerra 1 hora antes da decolagem. Não perca o prazo!

### Instrução 3
- Ícone: 📄
- Título: Documentos
- Descrição: Tenha em mão passaporte/RG, comprovante de vacinação e este bilhete.

### Instrução 4
- Ícone: 🔒
- Título: Segurança
- Descrição: Passe pela segurança com antecedência. Remova eletrônicos e líquidos.

### Instrução 5
- Ícone: 🚪
- Título: Portão de Embarque
- Descrição: Aguarde a chamada de embarque no portão indicado no painel de informações.

### Instrução 6
- Ícone: 🎫
- Título: Embarque
- Descrição: Apresente este bilhete e seu documento de identidade ao embarcar.

## ⚠️ Informações Importantes (Personalizáveis)

1. **Proibições**: Objetos cortantes, inflamáveis, explosivos e armas de fogo são proibidos em bagagem de mão e despachada.

2. **Líquidos**: Máximo 100ml por recipiente em bagagem de mão. Coloque em saco plástico transparente.

3. **Eletrônicos**: Baterias de lítio devem estar em bagagem de mão. Laptops e tablets devem ser retirados na segurança.

4. **Alterações**: Em caso de mudança de voo ou horário, entre em contato com a GOL imediatamente.

5. **Compensação**: Consulte nossa política de atrasos e cancelamentos em gol.com.br

## 📞 Informações de Contato (Rodapé)

```
Companhia Aérea:              GOL Transportes Aéreos Ltda.
Website:                      www.gol.com.br
Telefone:                     0300 115 2121
```

## 🔄 Processo de Atualização Rápida

1. Abra `index.html` em um editor de texto
2. Use Ctrl+H (Find and Replace) para substituir valores
3. Procure pelos valores antigos e substitua pelos novos
4. Salve o arquivo
5. Atualize o navegador para ver as mudanças
6. Exporte como PDF ou compartilhe o link

## 💡 Dicas de Eficiência

- **Crie templates por rota**: Salve versões diferentes para rotas frequentes
- **Use Find & Replace**: Mais rápido que edição manual
- **Mantenha um backup**: Guarde a versão original como referência
- **Teste no navegador**: Sempre visualize antes de compartilhar
- **Exporte em alta qualidade**: Use 100% de zoom ao exportar para PDF

## 📊 Estrutura de Pastas Recomendada

```
billing-templates/
├── gol-domestic/
│   ├── index.html
│   ├── bagagem-instrucoes.png
│   └── embarque-checklist.png
├── gol-international/
│   ├── index.html
│   ├── bagagem-instrucoes.png
│   └── embarque-checklist.png
└── templates-backup/
    └── original/
```

---

**Última atualização**: 04 de Março de 2026
