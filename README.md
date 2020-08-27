# Análise dos dados da PNAD Contínua com o Python

## A base de dados
Neste Notebook vamos analisar dados da Pesquisa Nacional por Amostra de Domicílios Contínua (PNADC).
A PNADC é uma pesquisa amostral levada à campo pelo 
Aqui analisazeremos os dados para o 4º trimestre de 2019.
Para saber mais sobre a PNADC acesse o site do IBGE: https://www.ibge.gov.br/estatisticas/sociais/populacao/9171-pesquisa-nacional-por-amostra-de-domicilios-continua-mensal.html .


Para o exercício realizado neste Notebook empregaremos os dados da PNAD de forma bruta, sem adequar os dados ao desenho amostral da pesquisa. O objetivo é realizar o exercício sem introduzir temas relativos ao desenho amostral complexo (que exigiria a aplicação de conceitos estatísticos específicos).

O plano amostral adotado na PNAD Contínua é conglomerado em dois estágios de seleção com estratificação das unidades primárias de amostragem (UPAs). Mais detalhes podem ser vistos na notas metodológicas: ftp://ftp.ibge.gov.br/Trabalho_e_Rendimento/Pesquisa_Nacional_por_Amostra_de_Domicilios_continua/Notas_metodologicas/notas_metodologicas.pdf .
