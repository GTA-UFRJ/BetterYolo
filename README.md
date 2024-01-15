# Rio de janeiro, 15 de Janeiro de 2024.

Grupo de Telecomunicação e Automação (GTA) - (COPPE/UFRJ)

# Autor(es): 
- Hugo Antunes
  
# Orientadores: 
- Professor Rodrigo de Souza Couto e
- Pedro Henrique Cruz Caminha

# Resumo
A detecção de objetos em tempo real é um desafio comum em diferentes contextos, como em carros autônomos e vigilância por câmeras de segurança. Entretanto, o processamento de vídeos em tempo real exige um alto poder computacional, essa exigência torna comum a ocorrência de atrasos. Essa demora afeta diretamente essas aplicações, já que elas necessitam que a detecção seja feita o quanto antes. Assim, esse artigo propõe uma comparação de quadros sequenciais por meio da utilização dos valores RGB de cada pixel. Aqueles quadros que forem julgados semelhantes não serão enviados para processamento, o que diminui significativamente o tempo de processamento.

# Comparação
Redução do envio de envios de quadros para processamento do YOLO, por meio do descarte de quadro similares. Esse descarte é feito por meio da função "Compare" que está encontrada no na classe myolo em codes/myolo.py
A similaridade é medida utilizando os valores RGB de cada pixel das duas imagens a serem comparadas.
