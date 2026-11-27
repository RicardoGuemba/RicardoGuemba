# Ricardo Haus Guembarovski

Desenvolvo soluções baseadas em Pesquisa Operacional e Inteligência Artificial pra solucionar problemas empresarias. Transformo imagens de câmeras e históricos de consumo em ferramentas de engenharia. Aqui você encontra aplicações que detectam, contam peças, medem distâncias, controlam processos visando otimização de processos industriais.

Sou engenheiro eletricista pela UDESC. Na UFSC, concluí o mestrado em Engenharia de Produção e o doutorado em Engenharia e Gestão do Conhecimento.


## Visão computacional e inspeção

**[Contagem de tubos](https://github.com/RicardoGuemba/CountRoofPipe)** · A partir de uma foto ou vídeo, o detector localiza os tubos e permite conferir visualmente cada peça contada.

- **Medição por câmera.** Para ajustar o foco com retorno sonoro, abra [Ajusta CAM](https://github.com/RicardoGuemba/ajusta_cam). Para calibrar a escala e medir distâncias em milímetros, abra [Pxmm CAM](https://github.com/RicardoGuemba/pxmm_cam).
- **Inspeção e movimento.** [Cromos](https://github.com/RicardoGuemba/Cromos) aplica detecção de defeitos a imagens de uma câmera Basler. [Surf Evolution](https://github.com/RicardoGuemba/Surf_Evolution) explora a associação entre surfista, prancha e pose em vídeo.
- **Treinamento de detectores.** [ObjectDetection DETR](https://github.com/RicardoGuemba/ObjectDetection_DETR) apresenta o fluxo de treino e avaliação. [RT-DETR](https://github.com/RicardoGuemba/RT-DETR) também documenta o empacotamento do aplicativo. Para configurações de treinamento em RTX 5080, consulte [CSV RT-DETR Deploy](https://github.com/RicardoGuemba/CSV_RT-DETR_DEPLOY).
- **Detecção de embalagens por plataforma.** Consulte a [edição Apple Silicon](https://github.com/RicardoGuemba/Buddme_DETR_mac) para o fluxo com Metal e a [edição NVIDIA RTX](https://github.com/RicardoGuemba/Buddme_RT-DETR_RTX) para o fluxo com CUDA.

## Automação industrial e robótica

**[Visão industrial para manuseio de embalagens](https://github.com/RicardoGuemba/Realtec_Vision_Buddmeyer)** · O sistema segmenta cada embalagem e estima sua posição e orientação para uma aplicação de pick-and-place integrada ao CLP.

- **Operação e controle espacial.** Para explorar a interface de operação, abra a [variante PySide](https://github.com/RicardoGuemba/Vision_Buddmeyer_PySide). Para consultar os materiais de sincronismo e controle espacial, abra o [projeto de visão 2109](https://github.com/RicardoGuemba/Projeto_VC_Buddmeyer_2109).
- **Calibração câmera–robô.** Comece por [Sincro Calibra Robô](https://github.com/RicardoGuemba/Sincro_Calibra_robo) para localizar o guia de implantação no PC industrial. O [Sincro Robô](https://github.com/RicardoGuemba/Sincro_robo) aponta diretamente para os testes do fluxo. Ambos documentam a relação entre a imagem da câmera e a pose lida do robô.
- **Detecção e contagem de eventos.** [RT-DETR Embalagens](https://github.com/RicardoGuemba/RT_DETR_Embalagens) documenta a detecção e o cálculo de centroide. [Pose Detection](https://github.com/RicardoGuemba/Pose_Detection) acompanha a sequência de retirada, leitura e depósito para contar ciclos completos.

## Demanda, estoques e simulação

**[Análise de demanda hospitalar](https://github.com/RicardoGuemba/Hospital_Demand_Distribution_Analyzer-)** · Explore o consumo intermitente de um produto, ajuste distribuições e simule o tempo até o estoque atingir o nível mínimo.

- **Previsão por produto.** [DK Oficial](https://github.com/RicardoGuemba/DK_Oficial) concentra o script ARIMA para intervalos de seis horas. [DK](https://github.com/RicardoGuemba/DK) reúne os experimentos de pré-processamento, histogramas e previsão em diferentes intervalos.
- **Preparação de movimentações.** O [simulador de demanda da DHS](https://github.com/RicardoGuemba/RHG_Gestao_Empresarial) transforma registros de movimentação em séries de consumo por produto.

## IA aplicada e engenharia de dados

**[Laboratório de personas com LLMs locais](https://github.com/RicardoGuemba/Laboratorio-personas-LLM)** · Configure os participantes de uma conversa ou debate em LM Studio e observe como seus perfis influenciam as respostas.

- **Simulação de atendimento.** O [Laboratório LLM SAC](https://github.com/RicardoGuemba/Laboratorio-LLM-SAC) aplica personas aos papéis de cliente e atendente, com recuperação de contexto.
- **Preparação de datasets.** Para combinar dois ZIPs com anotações COCO e reconciliar categorias, use o [mesclador COCO](https://github.com/RicardoGuemba/Merge_Dataset_COCO). Para unir conjuntos YOLO com pastas de imagens e rótulos, use o [mesclador Roboflow/YOLO](https://github.com/RicardoGuemba/merge-datasets-roboflow).

---

[Apresentação institucional da DHS](https://github.com/RicardoGuemba/Projeto.html) · [Contato pelo LinkedIn](https://www.linkedin.com/in/ricardo-haus-guembarovski-3777ba8/)
