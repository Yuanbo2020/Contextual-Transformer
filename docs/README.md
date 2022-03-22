<!-- 在此处写注释-->
<!--
<img src="../samples/Comparison_fig.1.png" width=50%/>
-->
# Model structure
![Image](model.png)
<div align="center"> 
The proposed contextual Transformer. In the forward and backward mask, the red, gray, and white blocks indicate the masked position of the information to be predicted, the position of the masked information, and the position of the available information.<br>
For the souce code, please see <a href="https://github.com/Yuanbo2020/Contextual-Transformer/tree/main/Code" 
target="https://github.com/Yuanbo2020/Contextual-Transformer/tree/main/Code">here</a>.
</div>

# Experimental results
## Results of the model with different ratios of N and M
![Image](different_ratios.png)
<br>
<br>
<br>

## Ablation experiments of the cTransformer on test set
![Image](ablation.png)
<br>
<br>
<br>

## The effect of different λ values on the cTransformer
![Image](different_lambda.png)
<br>
<br>
<br>

## Comparison of SAT and AT results with other methods related to the analysis of audio event sequences
![Image](other_models.png)
<br>
<br>
<br>

## Attention score
![Image](for_back_att.png)
<div align="center"> 
Attention score from the masked MHA in decoder. Subgraph (a) and (b) are from the normal and reverse sequence branches, respectively. The x-axis is each event predicted by the autoregressive way, y-axis is the corresponding reference event.
</div>
<br>
<br>
 
