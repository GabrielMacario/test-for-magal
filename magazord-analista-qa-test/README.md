<div align='center'>

![Magazord](LogoMagazord.png)

</div>

# Teste para vaga de Analista de Qualidade no Magazord.com.br
Este repositório tem como fim testar os candidatos para vaga de analista de qualidade na empresa [Magazord](https://magazord.com.br).

# 1º Cenário:

Você está trabalhando como Analista de Qualidade em um projeto de integração de marketplaces de terceiros, como Amazon e Mercado Livre, em um grande e-commerce. A equipe de desenvolvimento concluiu a implementação da integração e você é responsável por realizar os testes para garantir que a funcionalidade esteja funcionando corretamente.
Um detalhe importante, nessa integração, temos integração de estoque, anúncios, faturamento, pedidos e preço.

## Sua tarefa:

Descrever detalhadamente o plano de testes que você implementaria para validar a integração com o marketplace. Inclua no seu plano:

**1. Documentação e Materiais de Apoio:**
  - **Identificação da documentação:** Quais documentos e materiais de apoio serão utilizados para embasar o plano de testes? (Ex.: documentação oficial dos marketplaces, especificações técnicas da integração, requisitos do projeto, etc.)
  - **Análise da documentação:** Como você analisará a documentação para identificar os pontos de teste?
  - **Mapeamento dos requisitos:** Como você mapeará os requisitos da integração aos pontos de teste?
  - **Utilização de ferramentas:** Quais ferramentas serão utilizadas para auxiliar na análise da documentação e no mapeamento dos requisitos? (Ex.: ferramentas de gerenciamento de requisitos, ferramentas de análise de texto, etc.)

**2. Abrangência dos Testes:**
  - **Funcionalidades:** Quais funcionalidades da integração serão testadas?
  - **Casos de uso:** Quais casos de uso serão considerados para cada funcionalidade? (Ex.: cenários de sucesso, cenários de falha, cenários de carga, etc.)
  - **Priorização dos testes:** Quais critérios serão utilizados para priorizar os testes? (Ex.: criticidade da funcionalidade, impacto no negócio, riscos potenciais, etc.)

**3. Execução dos Testes:**
  - **Ambiente de teste:** Qual ambiente de teste será utilizado? (Ex.: ambiente de homologação, ambiente de produção, etc.)
  - **Dados de teste:** Como você obterá os dados de teste necessparios para os testes? (Ex.: dados de produtos, dados de pedidos, dados de usuários, etc.)
  - **Ferramentas de automação:** Quais ferramentas de automação serão utilizadas para executar os testes? (Ex.: ferramentas de teste funcional, ferramentas de teste de API, etc.)
  - **Registro de resultados:** Como você registrará os resultados dos testes? (Ex.: ferramenta de gerenciamento de testes, planilhas eletrônicas, etc.)

# 2º Cenário:

Você está trabalhando como Analista de Qualidade em um projeto de integração com a ferramenta de gerenciamento de estoque Bling em um grande e-commerce. A equipe de desenvolvimento concluiu a implementação da integração e você é responsável por realizar os testes para garantir que a funcionalidade esteja funcionando corretamente.

## Sua tarefa:

Descrever detalhadamente o plano de testes que você implementaria para validar a integração com a ferramenta Bling. Inclua no seu plano:

**1. Documentação e Materiais de Apoio:**
  - **Identificação da documentação:** Quais documentos e materiais de apoio serão utilizados para embasar o plano de testes? (Ex: documentação oficial da Bling, especificações técnicas da integração, requisitos do projeto, etc.)
  - **Mapeamento dos requisitos:** Como você mapeará os requisitos da integração aos pontos de teste?
  - **Utilização de ferramentas:** Quais ferramentas serão utilizadas para auxiliar na análise da documentação e no mapeamento dos requisitos? (Ex: ferramentas de gerenciamento de requisitos, ferramentas de análise de texto, etc.)

**2. Abrangência dos Testes:**
  - **Funcionalidades:** Quais funcionalidades da integração com a Bling serão testadas? (Ex: sincronização de produtos, atualização de estoque, processamento de pedidos, geração de relatórios, etc.)
  - **Priorização dos testes:** Quais critérios serão utilizados para priorizar os testes? (Ex: criticidade da funcionalidade, impacto no negócio, riscos potenciais, etc.)

**3. Execução dos Testes:**
  - **Dados de teste:** Como você obterá os dados de teste necessários para os testes? (Ex: dados de produtos, dados de estoque, dados de pedidos, etc.)
  - **Ferramentas de automação:** Quais ferramentas de automação serão utilizadas para executar os testes? (Ex: ferramentas de teste funcional, ferramentas de teste de API, etc.)
  - **Registro de resultados:** Como você registrará os resultados dos testes? (Ex: ferramenta de gerenciamento de testes, planilhas eletrônicas, etc.)

# 3º Cenário:

O cliente entrou em contato devido a uma questão relacionada aos seus anúncios. Quando os itens ficam sem estoque, em vez de serem marcados como "Pausado (sem estoque)", eles estão apenas sendo marcados como "Pausado", o que faz com que os anúncios permaneçam disponíveis para venda no Mercado Livre, mesmo sem estoque real. Isso está resultando em pedidos sendo feitos para itens sem estoque disponível, o que prejudica a reputação do cliente, pois ele precisa cancelar as vendas devido à falta de estoque.

Atualmente, o cliente possui 38 anúncios com a situação "Pausado", e ele relata que não os marcou manualmente como pausados.Quando enviamos uma atualização manual de estoque, o anúncio muda para a situação "Pausado sem estoque" e fica indisponível para venda no Mercado Livre.
Ao verificar o log dos anúncios, não encontramos registros de envio de informação de estoque igual a zero quando o estoque se esgota no Magazord.
Um exemplo de anúncio afetado é o seguinte: [MLB3097510082](https://produto.mercadolivre.com.br/MLB-3097510082-escultura-em-pedra-pirita-com-cupula-de-acrilico-_JM).
Envio em anexo um print do anúncio e um print do log, mostrando que não foram encontradas informações registradas na abertura da atividade.

Para o caso acima, descreva quais seriam os passos para analise e identificação do problema tendo em vista a documentação do próprio ML. Visto que não possui acesso ao painel seller do cliente e nem ao painel do mesmo no ERP Magazord, quais seriam as possíveis hipóteses do erro.

![anúncios pausado no magazord e sem estoque](aa.png)

# 4º Cenário:

Você está encarregado de testar a validação de dados cadastrais em um sistema de gerenciamento de usuários. O sistema possui os seguintes campos de cadastro:

- Nome completo
- E-mail
- Número de telefone
- Data de nascimento
- Endereço (com campos para rua, cidade, estado e CEP)

Houve alterações nos campos mencionados acima no cadastro do cliente, quais testes você faria para validar que o(s) campo(s) esta(ão) funcionando conforme esperado?

![Alterar pessoa](AlterarPessoa.png)

**Orientação:** Crie casos de teste para validar a entrada de dados nos campos modificados.

## Avaliação

> [!IMPORTANT]
> **Os candidatos serão avaliados com base na clareza, precisão e detalhamento das respostas.**

> [!IMPORTANT]
> **A capacidade de compreender e comunicar efetivamente requisitos e problemas é fundamental.**

> [!IMPORTANT]
> **A organização e a estrutura das respostas também serão consideradas na avaliação.**

## Envio do teste

> [!NOTE]
> **Suba o repositório no seu Github e envie o link diretamente para o seu recrutador.**

> [!WARNING]
> **Não serão aceitos alterações após o envio, caso precise de mais tempo para implementação do projeto alinhe com o seu recrutador com antecedência.**
