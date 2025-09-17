# Reducao_Dimensionalidade_Imagens
Processamento Simples de Imagens em Python Este projeto demonstra um script simples em Python para carregar, converter para níveis de cinza e binarizar uma imagem, exibindo os resultados e oferecendo a opção de salvar a imagem processada. Foram criados dois códigos, sendo um deles apenas para imagens .ppm pois não foi usada nenhuma biblioteca.
Processamento Simples de Imagens em Python
Este projeto demonstra um script simples em Python para carregar, converter para níveis de cinza e binarizar uma imagem, exibindo os resultados e oferecendo a opção de salvar a imagem processada.

Funcionalidades
Carregar uma imagem localmente no ambiente Google Colab.
Converter a imagem RGB para níveis de cinza.
Binarizar a imagem em níveis de cinza usando um threshold baseado na média dos pixels.
Exibir a imagem original, em níveis de cinza e binarizada.
Permitir ao usuário salvar a imagem combinada com os resultados.
Requisitos
Python 3.6+
Bibliotecas Python: tkinter, matplotlib, numpy, google.colab
As bibliotecas tkinter e google.colab são específicas para o ambiente Google Colab. Se você deseja executar este código localmente fora do Colab, será necessário ajustar o código para lidar com o carregamento e salvamento de arquivos de forma diferente (por exemplo, usando PIL ou cv2 para leitura/escrita de imagens e os para manipulação de arquivos).

Como Executar
Este código foi desenvolvido para ser executado no Google Colab. Siga os passos abaixo:

Abra este notebook no Google Colab.
Execute todas as células do notebook na ordem em que aparecem.
Quando a célula principal for executada, você será solicitado a selecionar uma imagem para processar. Clique no botão para fazer o upload da sua imagem.
O script processará a imagem e exibirá a imagem original, em níveis de cinza e binarizada.
Você será perguntado se deseja salvar a imagem combinada. Digite 's' para sim ou 'n' para não e pressione Enter.
Se você escolher salvar, será solicitado a digitar um nome para o arquivo de saída.
Código
O código está dividido em células para melhor organização no ambiente Colab:

Célula 1: Importa as bibliotecas necessárias.
Célula 2: Define as funções para carregar, ler, converter para cinza, binarizar, exibir e salvar imagens.
Célula 3: A célula principal que coordena a execução das funções, permitindo a interação com o usuário para carregar a imagem e decidir se deseja salvar os resultados.
Observações
A conversão para níveis de cinza utiliza os pesos padrão (0.299, 0.587, 0.114) para os canais R, G e B, respectivamente.
A binarização utiliza um threshold global calculado como a média dos valores de pixel da imagem em níveis de cinza.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests no repositório do GitHub.
