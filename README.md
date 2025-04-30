// 我们为SOCP任务构建了SOCP-Phone数据集。该数据集收集自京东平台，2021年11月1日至2024年1月15日期间发布的手机产品评论。有关SOCP-Phone的统计信息如下表：
// <数据统计表格>
// 我们提供了50个Phone-SOCP数据集的样本，在data/sample_50.json。完整的数据集和代码会在录用之后公布。

The Subject-Object-Category-Preference (SOCP) Quadruple Extraction task aims to extract quadruple comprising subject, object, category, and preference. We have built the SOCP-Phone dataset for the SOCP task. This dataset is collected from the JD platform, consisting of mobile phone product reviews posted between November 1, 2021, and January 15, 2024. The statistical information for SOCP-Phone is shown in the table below:

<table border="1">
  <thead>
    <tr>
      <th>#Categories</th>
      <th>Train</th>
      <th>Dev</th>
      <th>Test</th>
      <th>Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>#Comparative</td>
      <td>1680</td>
      <td>210</td>
      <td>210</td>
      <td>2100</td>
    </tr>
    <tr>
      <td>#Non-Comparative</td>
      <td>1680</td>
      <td>210</td>
      <td>210</td>
      <td>2100</td>
    </tr>
    <tr>
      <td>#Multi-Comparative</td>
      <td>590</td>
      <td>79</td>
      <td>69</td>
      <td>738</td>
    </tr>
    <tr>
      <td><strong>Total</strong></td>
      <td>3360</td>
      <td>499</td>
      <td>489</td>
      <td>4200</td>
    </tr>
  </tbody>
</table>

<br>

<table border="1">
  <thead>
    <tr>
      <th>#Elements</th>
      <th>Train</th>
      <th>Dev</th>
      <th>Test</th>
      <th>Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Subject</td>
      <td>1680</td>
      <td>210</td>
      <td>210</td>
      <td>2100</td>
    </tr>
    <tr>
      <td>Object</td>
      <td>1857</td>
      <td>230</td>
      <td>222</td>
      <td>2309</td>
    </tr>
    <tr>
      <td>Category</td>
      <td>2475</td>
      <td>313</td>
      <td>294</td>
      <td>3082</td>
    </tr>
    <tr>
      <td>Preference</td>
      <td>1876</td>
      <td>241</td>
      <td>235</td>
      <td>2352</td>
    </tr>
  </tbody>
</table>

<br>

<table border="1">
  <thead>
    <tr>
      <th>#Quadruples</th>
      <th>Train</th>
      <th>Dev</th>
      <th>Test</th>
      <th>Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>BETTER</td>
      <td>1963</td>
      <td>265</td>
      <td>257</td>
      <td>2485</td>
    </tr>
    <tr>
      <td>WORSE</td>
      <td>400</td>
      <td>49</td>
      <td>44</td>
      <td>493</td>
    </tr>
    <tr>
      <td>EQUAL</td>
      <td>200</td>
      <td>19</td>
      <td>17</td>
      <td>236</td>
    </tr>
    <tr>
      <td><strong>Total</strong></td>
      <td>2563</td>
      <td>333</td>
      <td>318</td>
      <td>3214</td>
    </tr>
  </tbody>
</table>

<br>

<table border="1">
  <thead>
    <tr>
      <th>#Quadruples</th>
      <th>#Comparative</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.53</td>
      <td>1.53</td>
    </tr>
  </tbody>
</table>


We provide 50 samples of Phone-SOCP in data/sample_50.json. The full dataset and code will be released after acceptance.
