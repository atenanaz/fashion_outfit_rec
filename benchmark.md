# Benchmark
 We have conducted extensive offline experiments to evaluate how the use of our proposed fashion outfit recommendation system affect the performance compared with state-of-the-art baseline end-to-end Siamese architecture. For the offline experiment, we are targeting the outfit compatibility prediction task, whose goal is to predict a compatibility score to a fashion outfit 
 
 Results of extensive experiments for the task outfit compatibility prediction on a publicly available dataset based on Polyvore indicates the merits of the proposed approach, which is able to improve the quality of Siamese-network more than 25\% independent of CNN type and a random recommender by 42\%.
 
 The feature extraction of Fashion items is implemented on MTLAB 2019 on MacBook pro $3.1$ GHz Intel Core $i7$. The pre-trained deep neural networks are used for feature extraction. Likewise, aggregation step and classification are done by MTLAB 2019. The generation of the baseline representations  (siamese network) is implemented on python $3.7$ and \emph{keras} frame work on the server by using common Python libraries (pandas, numpy and scikit-learn,).    
 
 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-7btt{font-weight:bold;border-color:inherit;text-align:center;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-9wq8"></th>
    <th class="tg-c3ow">20</th>
    <th class="tg-9wq8">50</th>
    <th class="tg-c3ow">100</th>
    <th class="tg-c3ow">Improvement<br>w.r.t main baseline</th>
  </tr>
  <tr>
    <td class="tg-c3ow">AlexNet</td>
    <td class="tg-c3ow">0.7061</td>
    <td class="tg-c3ow">0.7084</td>
    <td class="tg-7btt">0.7111</td>
    <td class="tg-c3ow">25.5% ↑</td>
  </tr>
  <tr>
    <td class="tg-c3ow">ResNet18</td>
    <td class="tg-c3ow">0.6871</td>
    <td class="tg-c3ow">0.6979</td>
    <td class="tg-7btt">0.7023</td>
    <td class="tg-c3ow">24% ↑</td>
  </tr>
  <tr>
    <td class="tg-c3ow">GoogleNet</td>
    <td class="tg-c3ow">0.7040</td>
    <td class="tg-7btt">0.7107</td>
    <td class="tg-c3ow">0.7098</td>
    <td class="tg-c3ow">27% ↑</td>
  </tr>
  <tr>
    <td class="tg-c3ow">VGG-16</td>
    <td class="tg-c3ow">0.6917</td>
    <td class="tg-c3ow">0.6934</td>
    <td class="tg-7btt">0.7003</td>
    <td class="tg-c3ow">24% ↑</td>
  </tr>
  <tr>
    <td class="tg-c3ow">VGG-19</td>
    <td class="tg-c3ow">0.6910</td>
    <td class="tg-c3ow">0.6929</td>
    <td class="tg-7btt">0.6972</td>
    <td class="tg-c3ow">22.5% ↑</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Siamese (Main baseline)</td>
    <td class="tg-c3ow" colspan="3">0.5667</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Random (baseline 2)</td>
    <td class="tg-c3ow" colspan="3">0.5004</td>
    <td class="tg-c3ow"></td>
  </tr>
</table>
