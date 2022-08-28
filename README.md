# tweet-sentiment-extraction_robert-base
Utilizing Robert-base to Extract support phrases for sentiment labels

> Selecting the part of the tweet (word or phrase) that reflects sentiment for the tweet

# `robert-base`
Pretrained model on Romanian language using a masked language modeling (MLM) and next sentence prediction (NSP) objective. 

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th align="center">Weights</th>
      <th align="center">L</th>
      <th align="center">H</th>
      <th align="center">A</th>
      <th align="center">MLM accuracy</th>
      <th align="center">NSP accuracy</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><em>RoBERT-base</em></td>
      <td align="center"><em>114M</em></td>
      <td align="center"><em>12</em></td>
      <td align="center"><em>768</em></td>
      <td align="center"><em>12</em></td>
      <td align="center"><em>0.6511</em></td>
      <td align="center"><em>0.9802</em></td>
    </tr>
  </tbody>
</table>

<hr>

## `References`
1. https://huggingface.co/readerbench/RoBERT-base
2. https://www.kaggle.com/abhishek/roberta-inference-5-folds/data
3. https://www.kaggle.com/shoheiazuma/tweet-sentiment-roberta-pytorch
4. https://www.kaggle.com/aditidutta/tweet-sentiment-extraction-pytorch
5. https://brunch.co.kr/@choseunghyek/7
6. https://vanche.github.io/spanbert_roberta/
7. https://www.kaggle.com/datasets/abhishek/roberta-base
