# 🏥 Plataforma Web — Vigilância Sanitária de Campinas

> **Desenvolvimento de uma Plataforma Web para Organização e Acesso aos Serviços da Vigilância Sanitária do Município de Campinas**

Trabalho de Conclusão de Curso (TCC) apresentado ao curso de **Tecnologia em Análise e Desenvolvimento de Sistemas** do **Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP) – Campus Campinas**.

---

## 📋 Sobre o Projeto

No município de Campinas, as orientações, legislações, formulários e procedimentos administrativos da Vigilância Sanitária encontram-se distribuídos em diferentes canais institucionais (como páginas da Prefeitura, portal do CVS-SP, SEI e VRE/REDESIM). 

Este projeto propõe a concepção, modelagem e prototipação de uma **plataforma web centralizada** que organiza o acesso às informações e facilita a tramitação de serviços sanitários, atendendo tanto ao público externo quanto à gestão interna da Prefeitura Municipal de Campinas (PMC).

> **Nota:** O escopo atual contempla o levantamento de requisitos, arquitetura, modelagem de dados e prototipação das interfaces (avaliadas por 101 participantes), servindo como base funcional e arquitetural para implementação futura.

---

## 👥 Perfis de Usuários e Funcionalidades

### 1. Cidadão / Estabelecimento
* **Consulta Centralizada:** Acesso unificado a serviços, orientações técnicas e legislações sanitárias vigentes.
* **Acompanhamento de Solicitações:** Visualização do andamento e das etapas de processos administrativos.
* **Gestão Documental:** Envio e armazenamento de arquivos vinculados aos processos.
* **Controle de Licenças:** Consulta de situação e datas de vencimento de licenças sanitárias.

### 2. Usuário Interno (Prefeitura Municipal de Campinas - PMC)
* **Análise Documental:** Conferência e gerenciamento de documentos enviados pelos estabelecimentos.
* **Monitoramento:** Acompanhamento da situação cadastral de estabelecimentos e licenças sanitárias.
* **Relatórios Gerenciais:** Visualização de indicadores e relatórios organizados por regiões e bairros do município.

---

## 🛠️ Arquitetura e Tecnologias Previstas

O projeto foi estruturado sob o padrão arquitetural **MVC (Model-View-Controller)**, visando a separação de responsabilidades, facilidade de manutenção e escalabilidade, em conformidade com as diretrizes de Governo Digital (Lei nº 14.129/2021) e da LGPD (Lei nº 13.709/2018).

| Camada | Tecnologias | Finalidade |
| :--- | :--- | :--- |
| **Front-end** | React, HTML5, CSS3, JavaScript | Estruturação, estilização responsiva e interatividade das interfaces |
| **Back-end / Serviços** | Firebase Authentication, Node.js *(opcional)* | Autenticação por perfil de acesso, regras de negócio e integrações |
| **Banco de Dados** | Cloud Firestore (Firebase) | Armazenamento em nuvem estruturado em coleções (`usuarios`, `estabelecimentos`, `processos`, `documentos`, `licencas`) |
| **Hospedagem** | Firebase Hosting | Publicação e disponibilidade da aplicação web |
| **Prototipação & Modelagem** | Canva, Draw.io, VS Code | Criação dos protótipos de tela e diagramas UML/conceituais |

---

## 📊 Resultados da Avaliação dos Protótipos

Os protótipos desenvolvidos foram avaliados por **101 participantes**, considerando os critérios de usabilidade da norma **ISO 9241-11** (efetividade, eficiência e satisfação):

* **87,1%** classificaram a proposta geral da plataforma como **ótima ou boa**.
* **82,1%** avaliaram positivamente (ótima ou boa) as **funcionalidades e relatórios gerenciais** destinados ao perfil PMC.

---

## 🎓 Autoria e Orientação

* **Autora:** Brenda Marques Bueno
* **Orientadora:** Profa. Ma. Zady Castaneda Salazar
* **Instituição:** Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP) – Campus Campinas
* **Ano:** 2026

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos. Sinta-se à vontade para consultar e referenciar este trabalho citando a autora.
