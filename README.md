# DIO_reducao_dimensionalidade

Projeto de redução de dimensionalidades de imagens implementado no Google Colab. Este projeto atende o que foi solicitado no Desafio do curso da **DIO: BairesDev - Machine Learnign Practicioner**

Foram utilizados os módulos:
- **files** de **google.colab**: para exibir um controle para upload da imagem desejada
- **imghdr**: para verificar se o arquivo uploaded é realmente uma imagem
- **cv2**: OpenCV, para converter a imagem em tons de cinza e para binarização
- **cv2_imshow** de **google.cloab.patches**: para exibir as imagens no Colab (o método cv2.imshow() de cv2 levanta exceção no Colab)

O projeto solicita do usuário o upload de uma imagem. Após o upload, a aplicação gera uma imagem em tons de cinza e outra binarizada a partir da original e as exibe em tela para download
