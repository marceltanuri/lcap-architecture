---
marp: true
theme: default
paginate: true
---

# Clássicos sobre Microserviços & DDD  
### Seleção para embasar PoC com arquitetura moderna  
Marcel, abril de 2025

---

## Clássicos da Engenharia de Software  
**Foco em DDD e modularização**

### *Domain-Driven Design* – Eric Evans  
- Divide sistemas por domínios (Bounded Contexts)  
- Linguagem ubíqua e modelo de domínio rico  
- **PoC 2:** justificativa para separação de Liferay Objects por domínio

---

### *Implementing Domain-Driven Design* – Vaughn Vernon  
- Aplicação prática de DDD moderno  
- Agregados, serviços, eventos e CQRS  
- **PoC 2:** estruturação clara e prática por contexto

---

### *Patterns of Enterprise Application Architecture* – Martin Fowler  
- Padrões como Repository, Service Layer, Event Publisher  
- **PoC 2:** abstrações úteis para encapsular acesso a Objects

---

## Livros O’Reilly & afins  
**Foco em Microserviços, EDA e sistemas distribuídos**

### *Building Microservices* – Sam Newman  
- Autonomia, deploy independente, escalabilidade  
- **PoC 1 e 2:** mostra problemas causados por Client Extensions e Objects centralizados

---

### *Monolith to Microservices* – Sam Newman  
- Estratégias para modularizar e quebrar com segurança  
- **PoC 2:** apoio para evolução sem ruptura

---

### *Designing Data-Intensive Applications* – Martin Kleppmann  
- Dados, eventos, logs, replicação e consistência  
- **PoC 1:** base conceitual para arquitetura orientada a eventos (EDA)

---

### *Microservices Patterns* – Chris Richardson  
- Saga, CQRS, Event Sourcing, API Gateway  
- **PoC 1:** comunicação entre domínios e orquestração via eventos

---

## Resumo Visual

- **DDD** organiza o interior dos domínios → *Evans, Vernon*  
- **EDA** organiza a comunicação entre domínios → *Kleppmann, Richardson*  
- **Modularização real** → *Sam Newman*  
- **Padrões de implementação** → *Fowler*

---

## Próximos passos

- Incorporar trechos ou referências desses livros no README da PoC  
- Usar argumentos e padrões como base técnica nas apresentações internas  
- Criar narrativa clara:  
  **“Não estamos reinventando a roda — estamos seguindo os clássicos.”**

---

# Obrigado!  
**Essa base teórica fortalece cada decisão técnica.**  
Pronto pra mostrar arquitetura com propósito.


---
