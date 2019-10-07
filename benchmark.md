# Benchmark
 We have conducted extensive offline experiments to evaluate how the use of our proposed fashion outfit recommendation system affect the performance compared with state-of-the-art baseline end-to-end Siamese architecture. For the offline experiment, we are targeting the outfit compatibility prediction task, whose goal is to predict a compatibility score to a fashion outfit 
 
 Results of extensive experiments for the task outfit compatibility prediction on a publicly available dataset based on Polyvore indicates the merits of the proposed approach, which is able to improve the quality of Siamese-network more than 25\% independent of CNN type and a random recommender by 42\%.
 
 The feature extraction of Fashion items is implemented on MTLAB 2019 on MacBook pro $3.1$ GHz Intel Core $i7$. The pre-trained deep neural networks are used for feature extraction. Likewise, aggregation step and classification are done by MTLAB 2019. The generation of the baseline representations  (siamese network) is implemented on python $3.7$ and \emph{keras} frame work on the server by using common Python libraries (pandas, numpy and scikit-learn,).    
 
 
<table>
  <tr>
    <th></th>
    <th>20</th>
    <th>50</th>
    <th>100</th>
    <th>Improvement<br>w.r.t main baseline</th>
  </tr>
  <tr>
    <td>AlexNet</td>
    <td>0.7061</td>
    <td>0.7084</td>
    <td>0.7111</td>
    <td>25.5% ↑</td>
  </tr>
  <tr>
    <td>ResNet18</td>
    <td>0.6871</td>
    <td>0.6979</td>
    <td>0.7023</td>
    <td>24% ↑</td>
  </tr>
  <tr>
    <td>GoogleNet</td>
    <td>0.7040</td>
    <td>0.7107</td>
    <td>0.7098</td>
    <td>27% ↑</td>
  </tr>
  <tr>
    <td>VGG-16</td>
    <td>0.6917</td>
    <td>0.6934</td>
    <td>0.7003</td>
    <td>24% ↑</td>
  </tr>
  <tr>
    <td>VGG-19</td>
    <td>0.6910</td>
    <td>0.6929</td>
    <td>0.6972</td>
    <td>22.5% ↑</td>
  </tr>
  <tr>
    <td>Siamese (Main baseline)</td>
    <td colspan="3">0.5667</td>
    <td></td>
  </tr>
  <tr>
    <td>Random (baseline 2)</td>
    <td colspan="3">0.5004</td>
    <td></td>
  </tr>
</table><table>
  <tr>
    <th></th>
    <th>20</th>
    <th>50</th>
    <th>100</th>
    <th>Improvement<br>w.r.t main baseline</th>
  </tr>
  <tr>
    <td>AlexNet</td>
    <td>0.7061</td>
    <td>0.7084</td>
    <td>0.7111</td>
    <td>25.5% ↑</td>
  </tr>
  <tr>
    <td>ResNet18</td>
    <td>0.6871</td>
    <td>0.6979</td>
    <td>0.7023</td>
    <td>24% ↑</td>
  </tr>
  <tr>
    <td>GoogleNet</td>
    <td>0.7040</td>
    <td>0.7107</td>
    <td>0.7098</td>
    <td>27% ↑</td>
  </tr>
  <tr>
    <td>VGG-16</td>
    <td>0.6917</td>
    <td>0.6934</td>
    <td>0.7003</td>
    <td>24% ↑</td>
  </tr>
  <tr>
    <td>VGG-19</td>
    <td>0.6910</td>
    <td>0.6929</td>
    <td>0.6972</td>
    <td>22.5% ↑</td>
  </tr>
  <tr>
    <td>Siamese (Main baseline)</td>
    <td colspan="3">0.5667</td>
    <td></td>
  </tr>
  <tr>
    <td>Random (baseline 2)</td>
    <td colspan="3">0.5004</td>
    <td></td>
  </tr>
</table>
