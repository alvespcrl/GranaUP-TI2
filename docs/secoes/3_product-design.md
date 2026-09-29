[⬅ Voltar ao índice](../README.md)

# Product Design

Nesse momento, vamos transformar os insights e validações obtidos em soluções tangíveis e utilizáveis. Essa fase envolve a definição de uma proposta de valor, detalhando a prioridade de cada ideia e a consequente criação de wireframes, mockups e protótipos de alta fidelidade, que detalham a interface e a experiência do usuário.

## Proposta de Valor

**Proposta de Valor - Lucas**

<img width="1620" height="964" alt="mapaLucas" src="https://github.com/user-attachments/assets/880b146f-ef6c-405b-8ce0-c72278368ab5" />

---

**Proposta de Valor - Rafael**

<img width="1620" height="964" alt="mapaRafael" src="https://github.com/user-attachments/assets/73b92193-383f-460c-9011-3efbcb8fafd2" />

---

**Proposta de Valor - Mariana**

<img width="577" height="346" alt="mapaMariana" src="https://github.com/user-attachments/assets/ecc39408-3bef-432d-8657-39fe40114128" />

---

## Requisitos

_Esta seção descreve os requisitos comtemplados nesta descrição arquitetural, divididos em dois grupos: funcionais e não funcionais._

### Requisitos Funcionais


| ID    | Descrição                                                                                                                    | Prioridade|
|-------|------------------------------------------------------------------------------------------------------------------------------|-----------|
| RF-01 | **Cadastro de usuário:** Permitir que o usuário crie uma conta informando nome, e-mail e senha.                              | Essencial |
| RF-02 | **Login:** Permitir o acesso seguro ao sistema utilizando credenciais cadastradas.                                           | Essencial |
| RF-03 | **Cadastro de objetivos:** Permitir criar metas financeiras informando nome, valor-meta, prazo e valor acumulado.            | Essencial |
| RF-04 | **Registro de lançamentos:** Permitir a inserção rápida de entradas (receitas) e saídas (despesas) unificadas.               | Essencial |
| RF-05 | **Gestão de lançamentos:** Permitir a edição, exclusão e categorização das movimentações cadastradas.                        | Essencial |
| RF-06 | **Dashboard financeiro:** Exibir a tela principal com foco no "Saldo Livre" atualizado e resumo visual de receitas/despesas. | Essencial |
| RF-07 | **Progresso dos objetivos:** Exibir visualmente o percentual de conclusão e o status de cada meta.                           | Essencial |
| RF-08 | **Simulador de cenários:** Calcular e exibir em tempo real o impacto de novos gastos no prazo das metas (Motor "E se?").     | Essencial |
| RF-09 | **Alertas contextuais:** Notificar o usuário de forma inteligente quando um gasto comprometer o andamento de um objetivo.    | Desejável |
| RF-10 | **Recomendações personalizadas:** Sugerir ações práticas para economia com base no comportamento e nas categorias de gasto.  | Desejável |


### Requisitos Não-Funcionais

| ID     | Descrição                                                                                                                                             |Prioridade|
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| RNF-01 | **Responsividade:** O sistema deve ser desenvolvido com abordagem *mobile-first*, adaptando-se perfeitamente a smartphones e desktops.                | Essencial|
| RNF-02 | **Usabilidade (Baixo Atrito):** A interface deve minimizar a digitação, priorizando botões rápidos e fluxos de no máximo 3 etapas para ações diárias. | Essencial|
| RNF-03 | **Desempenho:** O recálculo de prazos no Simulador de Cenários deve ocorrer de forma instantânea na interface web.                                    | Desejável|
| RNF-04 | **Restrição de Integração (R-03):** O sistema operará com lógica interna, sem consumir APIs externas de bancos (Open Finance) ou bots de WhatsApp.    | Essencial|

## Priorização de Requisitos

<img width="732" height="1024" alt="priorizacao" src="https://github.com/user-attachments/assets/0b7b5e43-fdd9-48f1-a7b7-9d3325cc9d9f" />


## Projeto de Interface

Artefatos relacionados com a interface e a interacão do usuário na proposta de solução.

### User Flow

Link do UserFlow

[UserFlow (Figma)](https://www.figma.com/board/RW1fNYqK8m0lLYT3X9bt91/Sem-t%25C3%25ADtulo?node-id=0-1&p=f&t=dmOtperCtmRDXNvF-0)


### Design System

<img width="1073" height="680" alt="design" src="https://github.com/user-attachments/assets/fc67195c-c263-48bc-957c-08efc5f68074" />

<img width="955" height="722" alt="design2" src="https://github.com/user-attachments/assets/58f30496-7299-4049-901a-20af9e7d27d0" />

<img width="956" height="713" alt="design3" src="https://github.com/user-attachments/assets/e7056f70-1b07-4b2b-be85-fd001be11073" />


### Wireframes

Estes são os protótipos de telas do sistemas.

<img width="937" height="521" alt="wireframe" src="https://github.com/user-attachments/assets/a01c72c8-d58d-428f-99e3-d6db371792a8" />


### Protótipo Interativo

✅ [Protótipo Interativo (Figma)](https://www.figma.com/design/UTIuqKThOG7pkuZxnWWyUN/GranaUP-%25E2%2580%2594-Prot%25C3%25B3tipo-Interativo?node-id=1-2&p=f&t=DuuAg4aULW8RXRhE-0)


---

[⬅ Anterior: Product Discovery](2_product-discovery.md) | [⬅ Voltar ao índice](../README.md) | [Próximo: Minimundo ➡](4_minimundo.md)
