# Relatório CAGED (tabelas) automatizado

## Três orientações: 

(1) O link "url <- "http://pdet.mte.gov.br/images/Novo_CAGED/2023/202308/3-tabelas.xlsx" provavelmente sofrerá mudanças ao longo do tempo. Perceba que ele indica ser um diretório que corresponde ao ano e mês, então provavelmente os próximos meses alterarão para 2023/09, 2023/10... e assim por diante. Na dúvida vá até o site do Caged (https://pdet.mte.gov.br/novo-caged) e confira o novo link. 

(2) Na linha 84 é que você escolhe para qual cidade pretende geral o relatório. 

(3) Caso queira um PDF sem scripts basta alterar os argumentos dos chunck echo=T para echo=F. 

Mensalmente, o Ministério do Trabalho divulga um relatório contendo dados sobre as movimentações no mercado de trabalho formal regido pela Consolidação das Leis do Trabalho (CLT). Estes dados estão disponíveis
em dois formatos: microdados acessíveis via FTP e tabelas em formato Excel disponibilizadas diretamente no portal do Ministério.

Trabalho com essas tabelas há quase dois anos e enfrentei desafios consideráveis em compreender a complexidade da formatação utilizada. As tabelas são frequentemente complicadas devido ao uso extensivo de
células mescladas, o que pode prejudicar a eficiência do trabalho, especialmente para analistas iniciantes.

Assim tomei a iniciativa de desenvolver um script em R que automatiza integralmente o processo de obtenção, carregamento, tratamento, visualização de dados em gráficos, geração de tabelas e criação de um relatório em formato PDF para qualquer cidade do Brasil.

Embora tenha demandado um esforço considerável, o resultado me agradou. A criação deste código de automação proporcionou uma notável melhoria na minha produtividade. Aquilo que costumava me consumir cerca de 40 minutos no início, hoje é resolvido com um único clique.
