# Digital Signature PDF Tool

Este projeto é uma aplicação que utiliza a biblioteca [iText](https://itextpdf.com/) para adicionar assinaturas digitais a arquivos PDF. Ele foi desenvolvido para facilitar a integração de funcionalidades de assinatura digital em aplicações.

## 🚀 Funcionalidades

- Assinatura digital de arquivos PDF.
- Validação de assinaturas existentes em PDFs.
- Suporte para diferentes tipos de certificados digitais.

## 🛠️ Tecnologias Utilizadas

- **C#**: Linguagem principal.
- **iText**: Biblioteca utilizada para manipulação e assinatura de PDFs (licenciada sob AGPL).
- **BouncyCastle**: Biblioteca adicional para criptografia.

## 📄 Licença

Este projeto utiliza a biblioteca iText sob a licença **AGPL (Affero General Public License)**. Isso significa que:

1. Todo o código-fonte deste projeto está disponível publicamente.
2. Qualquer modificação feita neste projeto também deve ser disponibilizada publicamente sob a licença AGPL.
3. Qualquer pessoa que utilizar este software, mesmo acessando-o remotamente (por exemplo, via uma API ou aplicação web), tem o direito de acessar o código-fonte.

Para mais informações sobre a licença AGPL, consulte o site oficial da [GNU AGPL](https://www.gnu.org/licenses/agpl-3.0.html).

## 📂 Estrutura do Repositório

```plaintext
.
├── src/               # Código-fonte do projeto
├── lib/               # Bibliotecas externas (iText, BouncyCastle, etc.)
├── resources/         # Arquivos de exemplo e certificados
├── LICENSE.md         # Licença AGPL
└── README.md          # Este arquivo
