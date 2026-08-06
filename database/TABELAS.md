# Estrutura Inicial das Tabelas

## municipios

- id
- nome
- estado
- regiao
- distancia
- empresa
- status

---

## contatos

- id
- municipio_id
- nome
- cargo
- telefone
- email

---

## maquinas

- id
- municipio_id
- marca
- modelo
- serie
- patrimonio
- horimetro

---

## licitacoes

- id
- municipio_id
- numero
- modalidade
- inicio
- fim
- empresa

---

## visitas

- id
- municipio_id
- vendedor
- data
- objetivo
- observacoes
- fotos

---

## vendedores

- id
- nome
- telefone
- email
- regiao

---

## usuarios

- id
- nome
- login
- senha
- perfil
