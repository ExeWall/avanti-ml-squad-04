# avanti-ml-squad-04

Projeto de Segmentação de Tumor Cerebral — Bootcamp em Machine Learning (Atlântico Avanti).

## Projeto 04 — Segmentação de Tumor Cerebral (Germ Cell Tumor)

**Dataset:** [Brain Tumor 12K MRI Images w Masks, Meta and Bbox](https://www.kaggle.com/datasets/fernando2rad/brain-tumor-12k-mri-images-w-masks-meta-and-bbox)

**Tumor analisado:** Germ Cell Tumor (Germinoma) — 263 imagens

### Estrutura

| Arquivo | Descrição |
|---------|-----------|
| `ATIV04_Segmentacao_Tumor_Cerebral.ipynb` | Notebook principal (ET-01 + ET-02 + ET-03) |
| `ET02_Germ_Cell_Tumor_Segmentation.ipynb` | Notebook da ET-02 (método da literatura) |

### Etapas

- **ET-01:** Análise do dataset (integridade, consistência, qualidade, distribuição, duplicatas)
- **ET-02:** Método da literatura (U-Net + ResNet34) e propostas de melhorias
- **ET-03:** Método próprio (U-Net + MobileNetV2 + Tversky Loss), comparação e conclusões

### Como Executar

1. Abrir o notebook `ATIV04_Segmentacao_Tumor_Cerebral.ipynb` no Google Colab
2. Ativar GPU: Runtime → Change runtime type → T4 GPU
3. Executar as células sequencialmente
4. Informar credenciais do Kaggle quando solicitado

### Equipe — Squad 04

- Alexia Nicoly de Moura Furtado
- Felipe Luiz da Silva Dias
- Igor Santana Sampaio
- Wallyson Rodrigues da Silva
