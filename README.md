# Loja Virtual ACME

## Descrição
Este projeto implementa uma loja virtual em Java para venda de downloads de músicas, vídeos e imagens. O sistema é construído seguindo os princípios de Clean Code e SOLID, com foco em uma arquitetura orientada a objetos e padrões de design.

## Estrutura do Projeto
### Classes de Modelo
- `Produto`: Representa os produtos (músicas, vídeos, imagens) com atributos como nome, arquivo e preço.
- `Cliente`: Armazena informações do cliente.
- `Assinatura`: Gerencia as assinaturas dos clientes, incluindo detalhes como mensalidade, data de início e término (opcional).
- `Pagamento`: Representa uma compra realizada pelo usuário, contendo a lista de produtos, data da compra e informações do cliente.

### Funcionalidades
1. **Criação de Produtos, Clientes e Pagamentos**: O sistema permite criar e gerenciar produtos, clientes e pagamentos.
2. **Ordenação de Pagamentos**: Os pagamentos são ordenados e exibidos por data.
3. **Cálculo de Valores**: Implementa cálculos de soma dos valores de pagamentos e valor total dos pagamentos.
4. **Relatórios de Vendas**: Fornece relatórios sobre a quantidade de cada produto vendido.
5. **Mapeamento Cliente-Produto**: Cria um mapa associando clientes a produtos comprados.
6. **Análises Financeiras**: Inclui funcionalidades para identificar o cliente que mais gastou, total faturado em um mês específico, e cálculos relacionados a assinaturas.

### Implementação de Assinaturas
- Diversos tipos de assinaturas (anual, semestral, trimestral) foram implementados.
- Métodos para calcular taxas baseadas no tipo de assinatura.
- Controle de assinaturas com atraso no pagamento e validação de clientes para novas compras.

### Padrões de Projeto GoF Utilizados
- Padrões Criacionais, Estruturais e Comportamentais foram aplicados para resolver problemas específicos do projeto.

## Clean Code e SOLID
- O código foi refatorado para aderir aos princípios SOLID e práticas de Clean Code.
- Classes foram projetadas para serem coesas, com baixo acoplamento e bom uso de encapsulamento.

## Qualidade do Código
- O código foi analisado com SonarQube para garantir a qualidade e manutenção.
- Os resultados da análise do SonarQube estão disponíveis na pasta `sonar`.

## Versionamento
- O código foi versionado em um repositório/branch separado para manter a organização e histórico de mudanças.

