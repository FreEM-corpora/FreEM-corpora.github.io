# Lemmatisation, POS-tagging and morphology models

## Use the model

- With Pie-extended: cf. [here](https://pypi.org/project/pie-extended/)
- Online: cf. [deucalion](https://dh.chartes.psl.eu/deucalion/freem)

## Results

Accuracies are the following (v.1) for lemmas:

<table border="1">
    <thead>
      	<tr><th colspan="7">Orig</th></tr>
        <tr>
          	<th></th>
          	<th>16</th>
            <th>17</th>
            <th>18</th>
            <th>19</th>
            <th>20</th>
          	<th>All</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Drama</th>
            <td>94.73</td>
          	<td>97.42</td>
          	<td>97.47</td>
          	<td>98.56</td>
          	<td>97.86</td>
          	<td bgcolor="red">97.25</td>
        </tr>
        <tr>
            <th>Varia</th>
            <td>96.23</td>
          	<td>98.09</td>
          	<td>98.27</td>
          	<td>98.23</td>
          	<td>97.46</td>
          	<td bgcolor="red">97.66</td>
        </tr>
        <tr>
            <th>Both</th>
            <td>95.51</td>
          	<td>97.76</td>
          	<td>97.88</td>
          	<td>98.39</td>
          	<td>97.66</td>
          	<td bgcolor="red">97.46</td>
        </tr>
    </tbody>
    <thead>
      	<tr><th colspan="7">Norm</th></tr>
        <tr>
          	<th></th>
          	<th>16</th>
            <th>17</th>
            <th>18</th>
            <th>19</th>
            <th>20</th>
          	<th>All</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Drama</th>
            <td>97.36</td>
          	<td>98.41</td>
          	<td>98.51</td>
          	<td>98.56</td>
          	<td>97.86</td>
          	<td bgcolor="red">98.15</td>
        </tr>
        <tr>
            <th>Varia</th>
            <td>98</td>
          	<td>98.4</td>
          	<td>98.54</td>
          	<td>98.23</td>
          	<td>97.46</td>
          	<td bgcolor="red">98.13</td>
        </tr>
        <tr>
            <th>Both</th>
            <td>97.69</td>
          	<td>98.4</td>
          	<td>98.53</td>
          	<td>98.39</td>
          	<td>97.66</td>
          	<td bgcolor="red">98.14</td>>
        </tr>
    </tbody>
</table>

Accuracies are the following (v.1) for POS:

<table border="1">
	  <thead>
      	<tr><th colspan="7">Orig</th></tr>
        <tr>
          	<th></th>
          	<th>16</th>
            <th>17</th>
            <th>18</th>
            <th>19</th>
            <th>20</th>
          	<th>All</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Drama</th>
            <td>90.34</td>
          	<td>94.47</td>
          	<td>94.64</td>
          	<td>95.03</td>
          	<td>93.71</td>
          	<td bgcolor="red">93.69</td>
        </tr>
        <tr>
            <th>Varia</th>
            <td>89.85</td>
          	<td>93.44</td>
          	<td>95.98</td>
          	<td>92.24</td>
          	<td>94.03</td>
          	<td bgcolor="red">93.14</td>
        </tr>
        <tr>
            <th>Both</th>
            <td>90.08</td>
          	<td>93.95</td>
          	<td>95.33</td>
          	<td>93.65</td>
          	<td>93.87</td>
          	<td bgcolor="red">93.41</td>>
        </tr>
    </tbody>
	  <thead>
      	<tr><th colspan="7">Norm</th></tr>
        <tr>
          	<th></th>
          	<th>16</th>
            <th>17</th>
            <th>18</th>
            <th>19</th>
            <th>20</th>
          	<th>All</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Drama</th>
            <td>93.69</td>
          	<td>95.75</td>
          	<td>95.61</td>
          	<td>95.03</td>
          	<td>93.71</td>
          	<td bgcolor="red">94.76</td>
        </tr>
        <tr>
            <th>Varia</th>
            <td>92.52</td>
          	<td>94.81</td>
          	<td>95.98</td>
          	<td>92.24</td>
          	<td>94.03</td>
          	<td bgcolor="red">93.94</td>
        </tr>
        <tr>
            <th>Both</th>
            <td>93.08</td>
          	<td>95.28</td>
          	<td>95.8</td>
          	<td>93.65</td>
          	<td>93.87</td>
          	<td bgcolor="red">94.35</td>
        </tr>
    </tbody>
</table>
