# 📚 Dicionário de Dados

## Estrutura dos Dados

| Campo | Tipo de Dado | Formato/Exemplo | Descrição | Valores Possíveis |
|-------|-------------|----------------|-----------|------------------|
| **Nome.Empregado** | Texto (String) | Isis, Emanuel, João Guilherme | Nome completo do funcionário | Texto livre |
| **ID** | Numérico (Inteiro) | 1304055947, 1109029366 | Número único de identificação do funcionário | Números de 10 dígitos |
| **Perf.Score.ID** | Numérico (Inteiro) | 1, 2, 3, 4 | Identificador numérico da categoria de performance | 1-4 (1=Abaixo, 2=Abaixo, 3=Dentro, 4=Acima) |
| **Salario** | Numérico (Decimal) | 5060, 3520, 4400 | Valor do salário mensal em reais (sem formatação) | Valores numéricos positivos |
| **Cargo** | Texto (String) | Técnico de Produção I, Analista Comercial I | Função/cargo exercido na empresa | Texto livre |
| **Data.Nascimento** | Data | 21/05/1982, 21/12/1975 | Data de nascimento do funcionário | DD/MM/AAAA |
| **Sexo** | Texto (Char) | F, M | Gênero do funcionário | F = Feminino, M = Masculino |
| **Estado.Civil** | Texto (String) | Solteiro, Casado(a) | Estado civil do funcionário | Solteiro, Casado(a) |
| **Data.Contratacao** | Data | 01/09/2015, 03/02/2015 | Data de admissão na empresa | DD/MM/AAAA |
| **Data.Saida** | Data | (vazio para ativos) | Data de desligamento da empresa | DD/MM/AAAA ou vazio |
| **Motivo.Saida** | Texto (String) | N/A - Empregado | Razão do desligamento | "N/A - Empregado" para ativos |
| **Status.Integrante** | Texto (String) | Ativo | Status atual do funcionário na empresa | Ativo, Inativo |
| **Departamento** | Texto (String) | Produção, Vendas, Administrativo | Departamento/área de atuação | Produção, Vendas, Administrativo |
| **Fonte.Recrutamento** | Texto (String) | Site da Empresa, Site de Vagas | Canal de recrutamento utilizado | Site da Empresa, Site de Vagas, Indicação Funcionários, Feira de Contratação |
| **Registro.Performance** | Texto (String) | Acima do Esperado, Dentro do Esperado | Avaliação qualitativa de performance | Abaixo do esperado, Dentro do Esperado, Acima do Esperado |
| **Pesquisa.Engajamento** | Numérico (Decimal) | 5, 1.12, 3.39 | Pontuação da pesquisa de engajamento | 1.0 a 5.0 |
| **Indice.Satisfacao** | Numérico (Decimal) | 5, 3, 2 | Índice de satisfação do funcionário | 1 a 5 |
| **Special.Projects.Count** | Numérico (Inteiro) | 0 | Quantidade de projetos especiais participados | Números inteiros |
| **Ultima.Atualizacao.Performance** | Data | 01/12/2016 | Data da última avaliação de performance | DD/MM/AAAA |
| **Ano.Contratacao** | Numérico (Inteiro) | 2015, 2017, 2018 | Ano de contratação extraído da data de contratação | AAAA |
| **Ano.Saida** | Numérico (Inteiro) | (vazio para ativos) | Ano de saída extraído da data de saída | AAAA ou vazio |
| **Tempo.Medio** | Numérico (Decimal) | 4.3, 4.9, 2.5 | Tempo médio de permanência na empresa em anos | Números decimais positivos |
