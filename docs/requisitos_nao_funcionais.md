# Requisitos Não Funcionais

## 1. Tecnologias

| Código   | Requisito             | Funcionalidade                                                                                                                   | Propriedade | Status                 |
| :------: | --------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------- | ---------------------- |
| **NF01** | Usar `Python`         | Linguagem usada no `back-end`                                                                                                    | Essencial   | 🔧 Em desenvolvimento |
| **NF02** | Usar `Flask`          | MicroFrameWork `python` usado na integração com o `front-end` e `back-end`                                                       | Essencial   | 🔧 Em desenvolvimento |
| **NF03** | Usar `HTML`           | Linguagem de marcação de hiper-textos utilizada na construção do site                                                            | Essencial   | 🔧 Em desenvolvimento |
| **NF04** | Usar `CSS`            | Linguagem utilizada na estilização do site                                                                                       | Essencial   | 🔧 Em desenvolvimento |
| **NF05** | Usar `ReactJS`        | Biblioteca `JavaScript` para a criação de interfaces                                                                             | Essencial   | 🔧 Em desenvolvimento |
| **NF06** | Usar `MySQL`          | Tipo de banco de dados relacional utilizado para armazenar informações                                                           | Essencial   | 🔧 Em desenvolvimento |
| **NF07** | Usar `Git` e `GitHub` | Ferramentas utilizadas para versionamento e compartilhamento do projeto para melhorar e otimizar o desenvolvimento da plataforma | Importante  | 🔧 Em desenvolvimento |
| **NF08** | Usar `Figma`          | Plataforma utilizada na criação do design das páginas antes na estilização com CSS                                               | Importante  | 🔧 Em desenvolvimento |
| **NF09** | Usar _framework da IA_ | ... | Essencial | ⏳ Planejando |
| **NF10** | Usar API da _LLM escolhida_ | ... | Essencial | ⏳ Planejando |
<!-- | **RNT07** | Usar `Docker`         | Plataforma utilizada para containerização e gerenciamento de ambientes de desenvolvimento                                        | ⏳ Planejando         | -->

## 2. Inteligencia Artificial

### Frameworks

1. **LangChain**

    Muito famosa

2. **CrewAI**

    Muito conhecida também

3. **Agno**

    Nova e aparentemente bem simples e configurável

### LLMs

1. **Llama 2**

    Grátis, porém roda localmente...

2. **ChatGPT**

    A versão PRO custa 20 dolares por mês. Muito usado e famoso, domina todos os testes de performance

3. **Perplexity**

    A versão PRO custa 20 dolares por mês. Se popularizando entre estudantes, pela sua característica de buscar as fontas dos resultados mostrados

## 3. Performance

| Código   | Requisito                                             | Propriedade | Status                 |
| :------: | ----------------------------------------------------- | ----------- | -----------------------|
| **NF11** | Usar geração aumentada de recuperação (**RAG**)       | Essencial   | 🔧 Em desenvolvimento |
| **NF12** | Resposta em até 2 segundos para 95% das requisições   | Importante  | ⏳ Planejando         |
| **NF13** | Resposta em até 5 segundos para 99% das requisições   | Importante  | ⏳ Planejando         |
| **NF14** | Resposta em até 10 segundos para 100% das requisições | Importante  | ⏳ Planejando         |

## 4. Escalabilidade

<!-- | Código    | Requisito                              | Status         |
| :-------: | -------------------------------------- | -------------- |
| **RNF01** | Suporte para 100 usuários simultâneos  | ⏳ Planejando |
| **RNF02** | Suporte para 500 usuários simultâneos  | ⏳ Planejando |
| **RNF03** | Suporte para 1000 usuários simultâneos | ⏳ Planejando | -->

...

## 5. Confiabilidade

...

## 6. Segurança

| Código   | Requisito                                                        | Propriedade | Status                 |
| :------: | ---------------------------------------------------------------- | ----------- | ---------------------- |
| **NF15** | Implementar criptografia SSL/TLS para todas as comunicações      | Importante  | ⏳ Planejando         |
| **NF16** | Armazenar senhas utilizando hashing seguro com `Argon2`          | Importante  | 🔧 Em desenvolvimento |
| **NF17** | Implementar autenticação multifator (MFA) para acessos sensíveis | Desejável   | ⏳ Planejando         |

...

## 7. Privacidade

| Código   | Requisito                                   | Propriedade | Status                 |
| :------: | ------------------------------------------- | ----------- | ---------------------- |
| **NF18** | Permitir que os usuários excluam seus dados | Essencial   | 🔧 Em desenvolvimento |

...

## 8. Usabilidade

| Código   | Requisito                                       | Propriedade | Status                 |
| :------: | ----------------------------------------------- | ----------- | ---------------------- |
| **NF19** | Interface intuitiva e fácil de navegar          | Importante  | 🔧 Em desenvolvimento |
| **NF20** | Compatível com dispositivos móveis (responsivo) | Importante  | 🔧 Em desenvolvimento |
<!-- | **RNF31** | Atender aos padrões de acessibilidade (ex: WCAG 2.1) | ⏳ Planejando | -->

...

## 9. Manutenibilidade

| Código   | Requisito                        | Propriedade | Status                 |
| :------: | -------------------------------- | ----------- | ---------------------- |
| **NF21** | Código documentado e comentado   | Importante  | 🔧 Em desenvolvimento |
| **NF22** | Estrutura modular e reutilizável | Importante  | 🔧 Em desenvolvimento |

...

## 10. Custo operacional

| Código   | Requisito                                                            | Propriedade | Status         |
| :------: | -------------------------------------------------------------------- | ----------- | -------------- |
| **NF23** | Utilizar serviços em nuvem com custo-benefício (ex: AWS, GCP, Azure) | ... | ⏳ Planejando |
| **NF24** | Monitorar e otimizar o uso de recursos para minimizar custos         | Importante  | ⏳ Planejando |

...

## 11. Páginas

| Código   | Página            | Funcionalidade                                                                                  | Propriedade | Status                  |
| :------: | ----------------- | ----------------------------------------------------------------------------------------------- | ----------- | ----------------------- |
| **NF25** | Home              | Página inicial do site (Landing Page), para mostrar as funcionalidades                          | Essencial   | 🔧 Em desenvolvimento  |
| **NF26** | Login             | Autenticação do usuário                                                                         | Essencial   | 🔧 Em desenvolvimento  |
| **NF27** | Cadastro          | Registro de novos usuários                                                                      | Essencial   | 🔧 Em desenvolvimento  |
| **NF28** | Dashboard         | Área principal: criação e visualização de materiais, grupos, entre outras funcionalidades       | Essencial   | 🔧 Em desenvolvimento  |
| **NF29** | Perfil            | Visualização e edição do perfil do usuário                                                      | Essencial   | 🔧 Em desenvolvimento  |
| **NF30** | Históricos        | Visualização dos históricos do usuário                                                          | Essencial   | 🔧 Em desenvolvimento  |
| **NF31** | Sobre             | Informações sobre a plataforma                                                                  | Essencial   | 🔧 Em desenvolvimento  |
| **NF32** | Configurações     | Configurações do usuário e preferências da IA                                                   | Essencial   | 🔧 Em desenvolvimento  |
