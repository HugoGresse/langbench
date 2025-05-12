# LangBench

LangBench is a simple benchmarking tool that processes numeric data and computes a mathematical result.

## Benchmark

### Hardware Specifications

**Processor**: aarch64

**Cores**: 4

### Data

**Size**: 534 MB

**Number of iterations:** 3

### Multithreaded

#### Results

<table><tr><th>Language</th><th>Elapsed Time (s)</th><th>System Time (s)</th><th>User Time (s)</th><th>CPU Usage (%)</th><th>Max Memory (MB)</th></tr><tr><td>c</td><td>2.08</td><td>0.03</td><td>8.22</td><td>396</td><td>535.38</td></tr><tr><td>rust</td><td>2.14</td><td>0.03</td><td>8.33</td><td>390</td><td>535.92</td></tr><tr><td>java</td><td>2.28</td><td>0.05</td><td>8.82</td><td>388</td><td>582.6</td></tr><tr><td>bunjs</td><td>2.32</td><td>0.19</td><td>8.47</td><td>372</td><td>597.58</td></tr><tr><td>nodejs</td><td>3.49</td><td>0.64</td><td>11.68</td><td>352</td><td>1426.96</td></tr><tr><td>python3.11</td><td>49.33</td><td>1.76</td><td>47.42</td><td>99</td><td>6968.54</td></tr></table>

#### CPU Usage Comparison

*A value of 100% indicates equal performance between the row and column languages.*

*A value of 50% indicates that the row language performs the computation twice as fast as the column language.*

<table><tr><th></th><th>c</th><th>rust</th><th>java</th><th>bunjs</th><th>nodejs</th><th>python3.11</th></tr><tr><th>c</th><td>100.0%</td><td>97.2%</td><td>91.23%</td><td>89.66%</td><td>59.6%</td><td>4.22%</td></tr><tr><th>rust</th><td>102.88%</td><td>100.0%</td><td>93.86%</td><td>92.24%</td><td>61.32%</td><td>4.34%</td></tr><tr><th>java</th><td>109.62%</td><td>106.54%</td><td>100.0%</td><td>98.28%</td><td>65.33%</td><td>4.62%</td></tr><tr><th>bunjs</th><td>111.54%</td><td>108.41%</td><td>101.75%</td><td>100.0%</td><td>66.48%</td><td>4.7%</td></tr><tr><th>nodejs</th><td>167.79%</td><td>163.08%</td><td>153.07%</td><td>150.43%</td><td>100.0%</td><td>7.07%</td></tr><tr><th>python3.11</th><td>2371.63%</td><td>2305.14%</td><td>2163.6%</td><td>2126.29%</td><td>1413.47%</td><td>100.0%</td></tr></table>

#### Memory Usage Comparison

*A value of 100% indicates equal memory usage between the row and column languages.*

*A value of 50% indicates that the row language uses half the memory of the column language.*

<table><tr><th></th><th>c</th><th>rust</th><th>java</th><th>bunjs</th><th>nodejs</th><th>python3.11</th></tr><tr><th>c</th><td>100.0%</td><td>99.9%</td><td>91.89%</td><td>89.59%</td><td>37.52%</td><td>7.68%</td></tr><tr><th>rust</th><td>100.1%</td><td>100.0%</td><td>91.99%</td><td>89.68%</td><td>37.56%</td><td>7.69%</td></tr><tr><th>java</th><td>108.82%</td><td>108.71%</td><td>100.0%</td><td>97.49%</td><td>40.83%</td><td>8.36%</td></tr><tr><th>bunjs</th><td>111.62%</td><td>111.51%</td><td>102.57%</td><td>100.0%</td><td>41.88%</td><td>8.58%</td></tr><tr><th>nodejs</th><td>266.53%</td><td>266.26%</td><td>244.93%</td><td>238.79%</td><td>100.0%</td><td>20.48%</td></tr><tr><th>python3.11</th><td>1301.61%</td><td>1300.29%</td><td>1196.11%</td><td>1166.13%</td><td>488.35%</td><td>100.0%</td></tr></table>

### Singlethreaded

#### Results

<table><tr><th>Language</th><th>Elapsed Time (s)</th><th>System Time (s)</th><th>User Time (s)</th><th>CPU Usage (%)</th><th>Max Memory (MB)</th></tr><tr><td>c</td><td>8.25</td><td>0.02</td><td>8.23</td><td>100</td><td>535.5</td></tr><tr><td>rust</td><td>8.38</td><td>0.02</td><td>8.35</td><td>99</td><td>535.88</td></tr><tr><td>bunjs</td><td>8.59</td><td>0.18</td><td>8.42</td><td>100</td><td>577.48</td></tr><tr><td>java</td><td>8.84</td><td>0.05</td><td>8.85</td><td>100</td><td>581.81</td></tr><tr><td>nodejs</td><td>11.65</td><td>0.19</td><td>11.47</td><td>100</td><td>589.12</td></tr><tr><td>python3.11</td><td>48.03</td><td>1.37</td><td>46.49</td><td>99</td><td>5899.75</td></tr></table>

#### CPU Usage Comparison

*A value of 100% indicates equal performance between the row and column languages.*

*A value of 50% indicates that the row language performs the computation twice as fast as the column language.*

<table><tr><th></th><th>c</th><th>rust</th><th>bunjs</th><th>java</th><th>nodejs</th><th>python3.11</th></tr><tr><th>c</th><td>100.0%</td><td>98.45%</td><td>96.04%</td><td>93.33%</td><td>70.82%</td><td>17.18%</td></tr><tr><th>rust</th><td>101.58%</td><td>100.0%</td><td>97.56%</td><td>94.8%</td><td>71.93%</td><td>17.45%</td></tr><tr><th>bunjs</th><td>104.12%</td><td>102.51%</td><td>100.0%</td><td>97.17%</td><td>73.73%</td><td>17.88%</td></tr><tr><th>java</th><td>107.15%</td><td>105.49%</td><td>102.91%</td><td>100.0%</td><td>75.88%</td><td>18.41%</td></tr><tr><th>nodejs</th><td>141.21%</td><td>139.02%</td><td>135.62%</td><td>131.79%</td><td>100.0%</td><td>24.26%</td></tr><tr><th>python3.11</th><td>582.18%</td><td>573.15%</td><td>559.14%</td><td>543.33%</td><td>412.27%</td><td>100.0%</td></tr></table>

#### Memory Usage Comparison

*A value of 100% indicates equal memory usage between the row and column languages.*

*A value of 50% indicates that the row language uses half the memory of the column language.*

<table><tr><th></th><th>c</th><th>rust</th><th>bunjs</th><th>java</th><th>nodejs</th><th>python3.11</th></tr><tr><th>c</th><td>100.0%</td><td>99.93%</td><td>92.73%</td><td>92.04%</td><td>90.9%</td><td>9.08%</td></tr><tr><th>rust</th><td>100.07%</td><td>100.0%</td><td>92.8%</td><td>92.11%</td><td>90.96%</td><td>9.08%</td></tr><tr><th>bunjs</th><td>107.84%</td><td>107.76%</td><td>100.0%</td><td>99.26%</td><td>98.02%</td><td>9.79%</td></tr><tr><th>java</th><td>108.65%</td><td>108.57%</td><td>100.75%</td><td>100.0%</td><td>98.76%</td><td>9.86%</td></tr><tr><th>nodejs</th><td>110.01%</td><td>109.94%</td><td>102.02%</td><td>101.26%</td><td>100.0%</td><td>9.99%</td></tr><tr><th>python3.11</th><td>1101.73%</td><td>1100.95%</td><td>1021.64%</td><td>1014.03%</td><td>1001.45%</td><td>100.0%</td></tr></table>

## Usage

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
./langbench.py --help
```

## Algorithm Description

The algorithm works as follows:

1. It reads pairs of integers from an input file.
2. For each pair of integers (`left[i]`, `right[i]`):
   - Computes `cos(left[i])`
   - Computes `sin(right[i])`
   - Multiplies these values together
   - Takes the absolute value of the result
   - Computes the square root of this value
3. Sums all these calculations to produce a final result

Mathematically, the algorithm computes:

```
result = ∑ sqrt(|cos(left[i]) * sin(right[i])|)
```

## Contributing

### Installation

**MacOS**:

```bash
brew install hadolint pre-commit
pre-commit install
```
