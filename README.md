<escape><h1 align="center">👥 Detecção de Faces em Grupo</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-success?style=for-the-badge" alt="Status Badge">
</p>

<p align="center">
  <i>Detecção de múltiplos rostos em uma imagem utilizando OpenCV.</i><br>
  <b>Autor:</b> Caetano Bordin
</p>

---

## 🧩 Sobre o Projeto

Este projeto utiliza **OpenCV** para detectar rostos em uma fotografia de um grupo de amigos. O programa identifica as faces presentes na imagem e desenha retângulos verdes ao redor de cada uma delas.

## 🧰 Tecnologias Utilizadas

- **Python**
- **OpenCV (cv2)**
- **Haar Cascade** — classificador para detecção de faces.

## ⚙️ Funcionalidades

- 🖼️ Leitura da imagem `4friends.jpg`;
- ⚫ Conversão da imagem para escala de cinza;
- 🔍 Detecção de múltiplos rostos;
- 🟩 Desenho de retângulos verdes ao redor das faces detectadas;
- 👥 Processamento de imagens com várias pessoas.

## 📚 Aprendizados

- Processamento de imagens com OpenCV;
- Conversão de cores com `cv2.cvtColor()`;
- Detecção de faces com `detectMultiScale()`;
- Utilização de parâmetros para ajustar a detecção;
- Desenho de retângulos com `cv2.rectangle()`.

## 🕹️ Como Executar

1. Instale o OpenCV:

```bash
pip install opencv-python
```

2. Coloque os arquivos `4friends.jpg` e `haarcascade_frontalface_default.xml` na mesma pasta do programa.

3. Execute o arquivo Python:

```bash
python main.py
```

4. Pressione qualquer tecla com a janela da imagem selecionada para encerrá-la.

## 📜 Licença

O código pode ser usado somente para **fins educacionais**.

É permitida a modificação e redistribuição, desde que os autores sejam citados e a licença original seja mantida.

O software é fornecido **"como está"**, sem garantias de qualquer tipo. Os autores não são responsáveis por danos decorrentes de seu uso.

## 👨‍💻 Autor

**Caetano Bordin**

🔗 [@Caetano-2012](https://www.github.com/Caetano-2012)

---</escape>
