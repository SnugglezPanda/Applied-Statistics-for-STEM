<h1>Module 8</h1>

-----------

<h4>Module 8 Overview</h4>
In Module Four, we studied how to perform hypothesis tests to test for
the difference of two population proportions and means. 

In this Module, the concept of hypothesis tesiting will be extended to three or more population means. 

### Zybooks Notes 8.1 One-way analysis of variance (one-way ANOVA)

<dl>
  <dt> <strong><em>One-way anaylsis of variance</em></strong> <em>(one-way ANOVA)</em>
    <dd>-determines wheterh a statistically significant difference exists among the means of three or more populations.</dd>
</dl>

<ul>
  <li> <strong>ANOVA</strong> tests for an association between a categorcial predictor variable and a response variable </li>
  <li> A factor can be a continuous variable partitioned into intervals commonly referred to as bins </li>
  <li> An <strong>ANOVA</strong> test is used to compare the means of three or more populations; as the test determines an association exists between pridctor variable and response variable </li>
  <li> Data scientists and statisticians refer to a possible value of a factor as a <strong>level</strong> </li>
  <li> A model can have multiple predictor variables; however ANOVA will only cover one predictor variable </li> 
  </ul>

<strong>One-way ANOVA</strong>

<em>Assumtions for one-way ANOVA</em>
<ul>
  <li> Independence. Samples should be independent and drawn randomly</li>
  <li> Normality. The underlying distribution of the populations from which the samples are drawn should be approximately noraml</li>
  <li> Homogeneity. The variances of the population distributions should be equal</li>
  </ul>

<em><strong>Procedure 8.1.1: One-way ANOVA</strong></em>
<ol>
  <li> Set the null and alternate hypotheses 
    <ol>
      <li>H<sub>0</sub> : u<sub>1</sub> = u<sub>2</sub> = ... = u<sub>i</sub>
        H<sub>a</sub> : u<sub>i</sub>!=u<sub>j</sub>, for some i!=j </li>
    </ol>
    where u<sub>1</sub> and u<sub>2</sub> are means from independent populations
  </li>
  <li> Use statistical software to find the test-statistic
    F = \frac{betwee-group variance}{within group variance}\
  <li> 
    

