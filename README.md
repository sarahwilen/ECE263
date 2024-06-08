# ECE263
LLM Evaluation: Using LLMs to Democratize Legal Assistance

## Files included
### Report-Democratizing Legal Assist using LLMs.pdf
Contains: Final project report
### Q&A Dataset.xlsx
Contains tabs:
<ul>
  <li><b>Dataset + Scores</b>: </li>
    <ul>
      <li>Full dataset containing:</li>
        <ul>
          <li>Practice Areas</li>
          <li>Base Questions</li>
          <li>Real Lawyer answers</li>
          <li>Reference links</li>
          <li>ChatGPT and Claude answers</li>
          <li>Augmented Question</li>
          <li>Human verified responses: Codes and Statutes</li>
          <li>ChatGPT and Claude answers to augmented question</li>
          <li>F1 Scores</li>
          <li>ChatGPT and Claude BERT Scores</li>
          <li>ChatGPT and Claude BLEURT Scores</li>
          <li>ChatGPT and Claude Flesch Reading Ease Scores</li>
          <li>ChatGPT and Claude Flesch Kincaid Grade Levels</li>
          <li>ChatGPT and Claude Lexical Diversity Scores</li>
          <li>ChatGPT and Claude Topic Coherence Scores</li>
        </ul>
    </ul>
  <li><b>Interpretability Dataset</b>: </li>
    <ul>
      <li>Reduced dataset containing only: </li>
        <ul>
          <li>Practice Areas</li>
          <li>Base Questions</li>
          <li>ChatGPT answers</li>
          <li>Claude answers</li>
        </ul>
    </ul>
  <li><b>US Census Educational Attainment Import</b>
    <ul>
      <li>Imported data from <a href="https://www.census.gov/data/tables/2022/demo/educational-attainment/cps-detailed-tables.html" title="U.S. Census Bureau: Table 1">U.S. Census Bureau: Table 1</a></li>
    </ul>
</ul>

### cs263_project_accuracy.py
Contains Code for:
<ul>
  <li>Bidirectional Encoder Representations from Transformers (BERT)</li>
  <li> Bilingual Evaluation Understudy Bidirectional Encoder Representations from Transformers (BLEURT)</li> 
    <ul>
      <li>Author: Alton Lee</li>
    </ul>
  <li>Flesch Reading Ease</li>
  <li>Flesch-Kinkaid Grade Level</li>
  <li>Topical Convergence using BERTopic (<i>Topical Convergence using BERTopic not used in Report, listed for clarity</i>)</li>
    <ul>
      <li>Author: Alyssa Simmons</li>
    </ul>
  <li>LLM as Judge</li> 
    <ul>
      <li>Author: Ruite Guo</li>
    </ul>
</ul>

### interpretability_scores.py
Contains: Code for:
<ul>
  <li>Lexical Diversity</li> 
    <ul>
      <li>Author: Sarah Wilen</li>
    </ul>
</ul>

### coherencelda.py
Contains: Code for:</li>
<ul>
  <li>Topical Convergence using Latent Dirichlet Allocation (LDA)</li>
    <ul>
      <li>Author: Alyssa Simmons</li>
    </ul>
</ul>
