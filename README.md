##Identificação de Espécies de Folhas – Dataset Flavia

Projeto acadêmico de Visão Computacional (2025.2)

## Resultado final
- **Melhor modelo**: SVM com kernel RBF + PCA → **95.6%** de acurácia (validação cruzada 5-fold)
- 34 espécies classificadas usando apenas características morfológicas e de textura

## Como executar
1. Coloque o dataset Flavia descompactado em `/content/drive/MyDrive/Flavia/Flavia` ou altere o caminho no notebook
2. Execute todas as células do notebook no Google Colab
3. O notebook já mostra as acurácias finais
## Imagens incluídas no repositório (pasta images/)
- `original_example.jpg` – imagem original do dataset`
- `gray.jpg` – conversão para tons de cinza`
- `threshold_otsu.jpg` – resultado da limiarização de Otsu`
- `mask_final.jpg` – máscara da folha após operações morfológicas`
- `contour.jpg` – contorno detectado sobre a imagem original`
- `pca_explained_variance.png` – gráfico da variância explicada pelo PCA`
