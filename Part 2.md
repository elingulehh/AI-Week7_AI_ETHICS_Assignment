PART 2: CASE STUDY ANALYSIS (40%)

CASE 1: BIASED HIRING TOOL

Scenario: Amazon’s AI recruiting tool penalized female candidates.

The Amazon's recruitment tool is a typical example of an AI model reflecting human biases with male applicants been considered for employments more than their female counterpart in a recruitment exercise. In this analysis our objective is to perform the following tasks;

TASK 1: IDENTIFY THE SOURCES OF BIASES (e.g., training data, model design); 

The key sources of bias that contributed to its discrimination behavior against female candidate includes;
 Presence of bias on the Trained data set resulted in gender imbalance among applicants because the model was trained to capture candidates who submitted resumes in the last 10 years most of which came from male applicants, reflecting the gender imbalance in the tech industry.Secondly, because successful hires in the past were predominantly men, the algorithm learned to associate male-related terms and experiences with success. Lack of fairness constraints or bias mitigation in the design allowed bias patterns to influence predictions unchecked. Lastly, Penalizing female indicators on Résumés that included words like “women’s” (e.g., “women’s chess club”) or listed all-women’s colleges were downgraded. This case is of using biased prediction to guide hiring will in no doubt amplify the gender imbalance over time.

TASK 2: PROPOSE THREE FIXES TO MAKE THE TOOL FAIRER.

To make the Amazon’s AI recruiting tool fairer and reduce gender bias, here are three smart and effective ways to consider in fixing this biases on the model:

1 Eliminate the bias on the trained data;
- Balanced representation: Ensure the dataset includes résumés from candidates of different genders, backgrounds, and career paths—not just past hires.
- Counterfactual data augmentation: Create synthetic variations of existing data that swap gender-specific terms and names to help the model learn neutral associations.
- Audit historical bias: Systematically review and remove patterns or features that reflect outdated or discriminatory hiring practices.

2. Revamp Model Architecture and Evaluation;
- Fairness-aware algorithms: Use modeling techniques that incorporate fairness constraints during training, like adversarial debiasing or equalized odds.
- Regular bias testing: Implement evaluation metrics to track disparate impact across gender and other demographic groups at every stage of development.
- Transparent feature selection: Actively monitor which résumé attributes the model considers most predictive—and cut out those that proxy for gender or other sensitive traits.

3. Human Oversight and Ethics Review;
- Diverse review panels: Include people from varied backgrounds to analyze model  
  behavior and flag biases the system might miss.
- Explainability tools: Give recruiters insights into why a candidate was recommended or rejected, making decisions traceable and accountable.
- Feedback loop: Let users flag questionable results and use that input to retrain and improve the model continuously.

TASK 3: SUGGEST METRICS TO EVALUATE FAIRNESS POST-CORRECTION
After successful attempt to correct bias from the model tool is achieved, the combination of both quantitative metrics and qualitative checks can then be applied to evaluate fairness. This reveals how the system treats different groups;

1. Statistical Parity (Demographic Parity);
- Measures whether different demographic groups (e.g. men vs. women) receive positive outcomes at similar rates.

- Goal: Equal selection rates across groups.

- Limitation: Doesn’t account for differences in qualifications.

2. Equal Opportunity;
- Focuses on qualified candidates: do equally qualified individuals from different groups have the same chance of being selected?

- Goal: Fair treatment of qualified applicants regardless of group membership.

3. Equality of Odds;
- Ensures that both true positive and false positive rates are equal across groups.

- Goal: Balanced accuracy and error rates for all demographics.

- Limitation: Can be hard to achieve without sacrificing model performance.

4. Predictive Parity;
- Compares the precision of predictions across groups (i.e. how often positive predictions are correct).

- Goal: Equal reliability of predictions for all groups.

5. Consistency Testing;
- Checks whether similar candidates receive similar outcomes.

- Goal: Stability and reliability in decision-making.

6. Fairness Score;
- A composite metric that aggregates multiple fairness indicators into a single score.

- Goal: Track fairness improvements over time.

These metrics help ensure that fairness is sustainable.


CASE 2: FACIAL RECOGNITION IN POLICING

Scenario: A facial recognition system misidentifies minorities at higher rates.

TASK 1: DISCUSS ETHICAL RISK e.g wrongful arrest, privacy violations

RESPONSE: Analyzing the scenario presented above in the contest of ethical risk such as in the case of wrongful Arrests and Convictions i will simply put that it is seen to be highly evident and most often time misidentification can lead to innocent individuals especially from minority groups being falsely accused or arrested, as seen in cases like Robert Williams and Nijeer Parks. Other similar occurance worth noting is the case of due process violation when facial recognition is treated as infallible, it can bypass proper investigative procedures, undermining legal safeguards. Furthermore, discrimination in surveillance occurs where minority communities may be disproportionately targeted, reinforcing systemic biases in law enforcement.The Use of biased technology such as this facial recognition system which  misidentifies minorities can violate anti-discrimination laws and privacy regulations which may result to organizations may facing lawsuits, fines, and enforcement actions and such organization is likely to loose public trust.


TASK 2:RECOMMEND POLICIES FOR RESPONSIBLE DEPLOYMENT:

RESPONSE: Here are policy recommendations for the responsible deployment of facial recognition systems in contexts where misidentification—particularly of minorities—is a risk. These are organized under key themes to ensure fairness, accountability, and transparency:

FAIRNESS AND ANTI-DISCRIMINATION POLICIES LEADING BIAS AUDITING AND MITIGATION:

- Mandate regular third-party bias audits across race, gender, and age groups.

- Disclose model performance metrics disaggregated by demographic group.

- Set accuracy thresholds for all groups, and do not deploy systems that fall below a 
  fairness standard.

TRANSPARENCY AND EXPLAINABILITY POLICIES LEADING TO RIGHT TO EXPLANATION AND DISCLOSURE REQUIREMENTS:

- Individuals misidentified or impacted must receive an explanation of how the system 
  made the decision.

- Organizations must clearly disclose the use of facial recognition to individuals, 
  especially in public or quasi-public spaces.

- Publish impact assessments and audit reports for public review.


PRIVACY AND DATA PROTECTION POLICIES AIDING DATA MINIMIZATION, CONSENT AND SECURE HANDLING 

- Collect only the minimum data necessary, and obtain informed, opt-in consent where 
  feasible.


- Enforce strict access controls, encryption, and time-limited storage of biometric 
  data.

