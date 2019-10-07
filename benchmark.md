# Benchmark
 We have conducted extensive offline experiments to evaluate how the use of our proposed fashion outfit recommendation system affect the performance compared with state-of-the-art baseline end-to-end Siamese architecture. For the offline experiment, we are targeting the outfit compatibility prediction task, whose goal is to predict a compatibility score to a fashion outfit 
 
 Results of extensive experiments for the task outfit compatibility prediction on a publicly available dataset based on Polyvore indicates the merits of the proposed approach, which is able to improve the quality of Siamese-network more than 25\% independent of CNN type and a random recommender by 42\%.
 
 The feature extraction of Fashion items is implemented on MTLAB 2019 on MacBook pro $3.1$ GHz Intel Core $i7$. The pre-trained deep neural networks are used for feature extraction. Likewise, aggregation step and classification are done by MTLAB 2019. The generation of the baseline representations  (siamese network) is implemented on python $3.7$ and \emph{keras} frame work on the server by using common Python libraries (pandas, numpy and scikit-learn,).    
 
 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-s6z2{text-align:center}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
  <caption> <font size="2"> Table: The best performing descriptor or combination of descriptors with respect to mean reciprocal rank (MRR), mean average precision (MAP), and recall (R) at two cutoff values (@4 and @10)</font> </caption>
  <tr>
    <th class="tg-s6z2"></th>
    <th class="tg-amwm">MRR@4</th>
    <th class="tg-amwm">MAP@4</th>
    <th class="tg-amwm">R@4</th>
    <th class="tg-amwm">MRR@10</th>
    <th class="tg-amwm">MAP@10</th>
    <th class="tg-amwm">R@10</th>
  </tr>
  <tr>
    <td class="tg-amwm">Best unimodal value</td>
    <td class="tg-baqh">0.0233</td>
    <td class="tg-baqh">0.0060</td>
    <td class="tg-baqh">0.0052</td>
    <td class="tg-baqh">0.0311</td>
    <td class="tg-baqh">0.0042</td>
    <td class="tg-baqh">0.0120</td>
  </tr>
  <tr>
    <td class="tg-amwm">Best unimodal feature</td>
    <td class="tg-baqh">i-vec</td>
    <td class="tg-baqh">i-vec</td>
    <td class="tg-baqh">i-vec</td>
    <td class="tg-baqh">i-vec</td>
    <td class="tg-baqh">i-vec</td>
    <td class="tg-baqh">i-vec</td>
  </tr>
  <tr>
    <td class="tg-amwm">Best multimodal value</td>
    <td class="tg-baqh">0.0266</td>
    <td class="tg-baqh">0.0072</td>
    <td class="tg-baqh">0.0059</td>
    <td class="tg-baqh">0.0359</td>
    <td class="tg-baqh">0.0049</td>
    <td class="tg-baqh">0.0139</td>
  </tr>
  <tr>
    <td class="tg-amwm">Best multimodal feature</td>
    <td class="tg-baqh">i-vec+tag</td>
    <td class="tg-baqh">i-vec+tag</td>
    <td class="tg-baqh">i-vec+tag</td>
    <td class="tg-baqh">i-vec+tag</td>
    <td class="tg-baqh">i-vec+tag</td>
    <td class="tg-baqh">i-vec+tag</td>
  </tr>
</table>
