# 📦 Agendamentos de Expedição - Apis Flora

Sistema de agendamento de expedição para gerenciar entregas das principais redes de clientes (Amazon, São Paulo, Pacheco).

## 🚀 Acesso Rápido

**URL de Acesso:** https://ApisFloraCom.github.io/agendamentos/

*(Atualize a URL com seu usuário do GitHub)*

## ✨ Funcionalidades

- ✅ Formulário de entrada com validação
- 📊 Tabelas por rede (Amazon, São Paulo, Pacheco)
- 🔍 Busca em tempo real por NF ou Pedido
- 🔗 Links diretos para rastreamento de transportadoras
- 💾 Dados sincronizados com Supabase
- 👥 Multi-usuário (múltiplas pessoas podem usar simultâneamente)
- 📱 Responsivo (funciona em celular, tablet e desktop)
- ⚡ Atualização em tempo real a cada 30 segundos

## 📋 Como Usar

### Primeira Configuração

1. Abra a aplicação no navegador
2. Clique na aba **⚙️ Config**
3. Preencha as credenciais do Supabase:
   - **URL do Supabase:** `https://tuonvfcqquxtbuaatjfu.supabase.co`
   - **Chave Anon do Supabase:** *(fornecida separadamente)*
4. Clique em **Salvar Configuração**

### Lançar um Agendamento

1. Clique na aba **➕ Entrada**
2. Preencha os campos obrigatórios (*):
   - Rede de Destino
   - Data do Pedido
   - Data SAP
   - Data Faturamento
   - NF (Nota Fiscal)
   - Data Expedição
3. Preencha os demais campos conforme necessário
4. Clique em **💾 Salvar Agendamento**

### Acompanhar Agendamentos

- Clique na aba da rede desejada (Amazon, São Paulo, Pacheco)
- Visualize todos os agendamentos com status
- Clique em **Rastrear** para abrir o link da transportadora

### Buscar Agendamento

- Vá para a aba **🔍 Pesquisa**
- Digite a NF ou Nº do Pedido
- Resultados aparecem instantaneamente

## 🔗 Transportadoras Suportadas

| Transportadora | Link | Credenciais |
|---|---|---|
| **ATIVA** | https://ativalog.com.br/area-do-cliente/ | CNPJ: 49345358000145<br>Senha: 4934 |
| **BRASPRESS** | https://www.braspress.com.br/w/tracking/ | CNPJ: 49345358000145 |
| **TROCA** | https://rastreamento.grupotroca.com.br | CNPJ: 49345358000145 |

## 📊 Dados Armazenados

Cada agendamento contém:
- Data Pedido
- Lead Time
- CD
- Data SAP
- Data Faturamento
- Nº NF
- Nº Pedido
- Data Solicitação
- Data Agendamento
- Data Reagendamento
- Data Expedição
- Transportadora
- Status
- Data Entrega
- Observações
- Tempo Total (calculado automaticamente)

## 🔒 Segurança

- Dados armazenados no Supabase (banco de dados confiável)
- Sincronização segura via API
- Cada rede tem dados isolados
- Histórico de quem criou/modificou

## 📱 Dispositivos Suportados

✅ Desktop (Chrome, Firefox, Safari, Edge)
✅ Tablet (iPad, Android Tablets)
✅ Celular (iPhone, Android)

## 🛠️ Troubleshooting

### "Configure o Supabase primeiro"
- Verifique se preencheu URL e Chave corretamente
- Clique em Salvar Configuração
- Atualize a página

### "Erro ao salvar"
- Verifique internet
- Confirme que a URL e Chave do Supabase estão corretas
- Tente novamente

### Dados não aparecem
- Aguarde 30 segundos (sincronização)
- Atualize a página
- Verifique se o Supabase tem dados na tabela

## 👥 Compartilhar com o Time

Basta enviar o link: **https://ApisFloraCom.github.io/agendamentos/**

Todos os usuários veem os mesmos dados em tempo real!

## 📞 Suporte

Para problemas ou sugestões, entre em contato com Rhuan.

---

**Versão:** 1.0  
**Última atualização:** Janeiro 2025  
**Tecnologia:** HTML5 + JavaScript + Supabase
