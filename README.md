## AWS-Academy-Lab--Amazon-EBS

<p align="center">
  <img src="images/amazon-ebs-lab.png" alt="Amazon EBS Lab" width="600">
</p>

<p align="center">
  <em>Amazon EC2 • Amazon EBS • Snapshot • Backup • Disaster Recovery</em>
</p>

### Sobre o Projeto

Este laboratório teve como objetivo explorar o funcionamento do Amazon Elastic Block Store (Amazon EBS), o serviço de armazenamento em bloco da AWS utilizado por instâncias do Amazon EC2.

Durante a atividade foram realizados procedimentos de criação, anexação, formatação, montagem e recuperação de volumes, simulando situações reais enfrentadas por administradores de infraestrutura em ambientes de nuvem.

---

### 🎯 Objetivos

- Criar um volume Amazon EBS
- Anexar o volume a uma instância Amazon EC2
- Criar e montar um sistema de arquivos Linux
- Persistir dados no volume
- Criar snapshots para backup
- Restaurar dados utilizando snapshots
- Validar a recuperação das informações

---

### Arquitetura

(Imagem da arquitetura)

---

### Tecnologias Utilizadas

- Amazon EC2
- Amazon EBS
- Amazon Snapshot
- Amazon S3 (armazenamento dos snapshots)
- Linux
- EC2 Instance Connect

---

### 🔧 Etapas Executadas

### 1. Criação do Volume EBS

Criação de um novo volume SSD (gp2), configurando zona de disponibilidade compatível com a instância EC2.

---

### 2. Associação do Volume

O volume foi anexado à instância utilizando o Console AWS.

---

### 3. Configuração do Sistema de Arquivos

Foram executados comandos Linux para:

- criar sistema de arquivos EXT3
- montar o volume
- configurar montagem automática
- validar armazenamento

---

### 4. Persistência dos Dados

Foi criado um arquivo dentro do volume para validar a gravação dos dados.

---

### 5. Backup

Criação de Snapshot do volume.

---

### 6. Recuperação

Foi criado um novo volume utilizando o Snapshot.

Após anexá-lo à instância, foi possível recuperar o arquivo anteriormente salvo.

---

### Principais Aprendizados

*Administração de armazenamento em nuvem

*Persistência de dados

*Recuperação de desastres

*Estratégias de Backup

*Amazon EBS

*Snapshots

*Linux File System

*Montagem de volumes

*Boas práticas em Infraestrutura como Serviço (IaaS)

---

### Conclusão

Este laboratório demonstrou como o Amazon EBS garante armazenamento persistente para instâncias EC2 e como os Snapshots possibilitam estratégias eficientes de backup, recuperação e continuidade de negócios.

Esses conceitos são fundamentais para arquiteturas resilientes na AWS, reduzindo riscos de perda de dados e aumentando a disponibilidade das aplicações.

### Autora

<p align="center">

**Eliana Diniz**

Analista de Dados | Power BI | AWS Cloud | IA Generativa | Snowflake

<a href="https://www.linkedin.com/in/eliana-diniz">
LinkedIn
</a> •
<a href="https://github.com/Dinizasilva">
GitHub
</a>

</p>

