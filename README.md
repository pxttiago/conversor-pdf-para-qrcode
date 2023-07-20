# conversor-pdf-para-qrcode
Este programa converte textos de arquivos no formato PDF para QRCode e salva como imagem.

Nota: Por padrão, a biblioteca qrcode suporta salvar imagens nos formatos PNG e SVG. Para salvar em JPG ou JPEG, é necessário instalar a biblioteca pillow, que é uma dependência da qrcode. O pillow permite que você salve o código QR em vários formatos de imagem, incluindo JPG e JPEG.

pip install pillow

Após instalar o pillow você poderá salvar o QRcode gerado em outros formatos de imagem alterando a linha conforme exemplo abaixo: 

img.save('codigo_qr.jpg')
