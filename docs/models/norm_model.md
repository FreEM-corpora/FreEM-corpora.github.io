# Normalisation models

## Use the model

## Results

<table border="1">
<thead>
  <tr>
    <th>Model</th>
    <th>Precision %</th>
    <th>Precision OOV %</th>
  </tr>
</thead>
<tbody>
  <tr>
    <th>Identity function</th>
    <td>72,40</td>
    <td>41,89</td>
  </tr>
  <tr>
    <th>ABA</th>
    <td>94.70</td>
    <td>67,51</td>
  </tr>
  <tr>
    <th>SMT</th>
    <td bgcolor="red"><b>96,83</b>±0,06</td>
    <td>73,41±0,16</td>
  </tr>
  <tr>
    <th>LSTM</th>
    <td>96,13±0,06</td>
    <td bgcolor="red"><b>74,52</b>±0,64</td>
  </tr>
  <tr>
    <th>Transformer</th>
    <td>96,03±0,06</td>
    <td>74,02±0,77</td>
  </tr>
  <tr>
    <th>Fonction d’identité + Le<span style="font-style:italic">fff</span></th>
    <td>85,80</td>
    <td>63,08</td>
  </tr>
  <tr>
    <th>ABA + Le<span style="font-style:italic">fff</span></th>
    <td>95,00</td>
    <td>71,54</td>
  </tr>
  <tr>
    <th>SMT + Le<span style="font-style:italic">fff</span></th>
    <td bgcolor="red"><b>97,00</b>±0,00</td>
    <td bgcolor="red"><b>76,04</b>±0,18</td>
  </tr>
  <tr>
    <th>LSTM + Le<span style="font-style:italic">fff</span></th>
    <td>96,27±0,06</td>
    <td bgcolor="red"><b>76,29</b>±0,29</td>
  </tr>
  <tr>
    <th>Transformer + Le<span style="font-style:italic">fff</span></th>
    <td>96,17±0,06</td>
    <td>75,56±0,32</td>
  </tr>
</tbody>
</table>
