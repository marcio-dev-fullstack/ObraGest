# 1️⃣ Definição Inicial do Sistema

## 🔹 Nome do App (exemplo)

**ObraGest – Sistema de Gestão para Engenharia Civil**

## 🔹 Objetivo do Aplicativo

Desenvolver um aplicativo para auxiliar engenheiros civis no gerenciamento de obras, controle de custos, cronograma, equipe e documentação técnica.

## 🔹 Público-alvo

* Engenheiros civis
* Mestres de obras
* Construtoras
* Escritórios de engenharia
* Estudantes de engenharia civil

---

# 2️⃣ Levantamento de Requisitos

A análise é dividida em:

* Requisitos Funcionais (RF)
* Requisitos Não Funcionais (RNF)
* Requisitos de Segurança
* Regras de Negócio

---

# 3️⃣ Requisitos Funcionais (RF)

São as funções que o sistema deve executar.

### RF-001 – Cadastro de Usuário

O sistema deve permitir:

* Cadastro de engenheiros
* Login com e-mail e senha
* Recuperação de senha

---

### RF-002 – Cadastro de Obras

O sistema deve permitir:

* Criar nova obra
* Inserir:

  * Nome da obra
  * Endereço
  * Cliente
  * Valor do contrato
  * Prazo
* Editar e excluir obras

---

### RF-003 – Controle de Cronograma

O sistema deve:

* Permitir criar etapas da obra
* Definir datas de início e término
* Mostrar progresso em %
* Exibir gráfico de andamento

---

### RF-004 – Controle de Custos

O sistema deve:

* Registrar despesas por categoria

  * Material
  * Mão de obra
  * Equipamentos
* Comparar custo previsto x realizado
* Gerar relatório financeiro

---

### RF-005 – Diário de Obra

O sistema deve:

* Permitir registro diário
* Anexar fotos
* Inserir observações técnicas
* Registrar condições climáticas

---

### RF-006 – Calculadora Técnica

O sistema deve incluir:

* Cálculo de volume de concreto
* Cálculo de área
* Cálculo de quantitativo de material

---

# 4️⃣ Requisitos Não Funcionais (RNF)

### RNF-001 – Segurança

* Criptografia de dados
* Autenticação segura
* Controle de acesso por perfil

### RNF-002 – Compatibilidade

* Android
* iOS
* Versão Web

### RNF-003 – Armazenamento

* Backup automático em nuvem
* Sincronização online/offline

### RNF-004 – Desempenho

* Resposta inferior a 3 segundos
* Capacidade para múltiplas obras simultâneas

---

# 5️⃣ Requisitos de Segurança

* Controle de acesso por nível:

  * Engenheiro
  * Técnico
  * Administrativo
* Logs de auditoria
* Proteção contra perda de dados

---

# 6️⃣ Regras de Negócio

* Uma obra deve estar vinculada a um engenheiro responsável.
* Uma despesa deve estar vinculada a uma obra.
* O valor executado não pode ultrapassar o valor contratado sem alerta.
* O cronograma deve permitir replanejamento.

---

# 7️⃣ Modelo Simplificado de Casos de Uso

### Caso de Uso: Criar Obra

**Ator:** Engenheiro
**Fluxo principal:**

1. Usuário faz login
2. Acessa “Nova Obra”
3. Preenche dados
4. Salva
5. Sistema confirma cadastro

---

# 8️⃣ Tecnologias Sugeridas (Desenvolver)

* Frontend: Flutter ou React Native
* Backend: Node.js ou Django
* Banco: PostgreSQL
* Cloud: AWS ou Firebase

---

# 9️⃣ Diferencial Estratégico (Se For Produto Comercial)

* Modo Offline (para canteiro sem internet)
* Assinatura digital de ART
* Integração futura com órgãos como:

  * Conselho Federal de Engenharia e Agronomia
    
  * Conselho Regional de Engenharia e Agronomia
