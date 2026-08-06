# BANCO DE DADOS

## Tabela: usuarios

- id
- nome
- email
- senha
- tipo (Administrador / Gestor / Vendedor)
- ativo

---

## Tabela: municipios

- id
- nome
- região
- distância
- população
- área
- empresa_responsável
- vendedor_responsável
- status
- potencial_comercial

---

## Tabela: administracao

- id
- municipio_id
- prefeito
- vice_prefeito
- secretario_obras
- secretario_agricultura
- comprador
- chefe_patio
- mecânico
- telefones
- emails

---

## Tabela: frota

- id
- municipio_id
- categoria
- marca
- modelo
- ano
- patrimônio
- horímetro
- situação

---

## Tabela: licitações

- id
- municipio_id
- número
- objeto
- modalidade
- abertura
- encerramento
- vigência
- status

---

## Tabela: visitas

- id
- municipio_id
- vendedor
- data
- objetivo
- resultado
- observações

---

## Tabela: agenda

- id
- vendedor
- data
- horário
- município
- atividade
- status

---

## Tabela: documentos

- id
- municipio_id
- categoria
- nome
- arquivo
