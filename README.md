Projeto feito através do curso do John Smilga de Node. Possui as seguintes funcionalidades:

- Permite o usuário postar imagens que ficam armazenadas em nuvem através do Cloudinary
- O usuário pode especificar o nome, preço e imagem do produto
- Projeto utiliza o banco de dados MongoDB através da biblioteca mongoose
- Imagens são manipuladas através da biblioteca express-fileupload

In order to run the project, in the root create .env with these two variables, with your own values.

MONGO_URI(obtained through mongoDB)
CLOUD_NAME(obtained through cloudinary)
CLOUD_API_KEY(obtained through cloudinary)
CLOUD_API_SECRET(obtained through cloudinary)

After that run this command

npm install && npm start
