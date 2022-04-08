# Actuarial_Policyholder_Projections_Data
Calculate the projected claims for the full duration of the policy for a block of business of 100 policy holders using VBA.

#### Background
An insurance provider offers a healthcare policy that covers medical, dental, and vision expenses.

This healthcare policy provides coverage for a maximum of 25 years or until the policyholder reaches age 70. This insurance provider does not offer this policy to individuals under 20 years old.

The average claim amount for a male is $687 and the average claim amount for a female is $492.

The probability of making a claim by age bracket for males is as follows:

Age   20s     30s     40s     50s     60s

Male  1.00%   1.50%   3.00%   5.00%   8.00%

Females are 25% less likely to make a claim at any given age. So, females will always have a lower probability of making a claim.

The probability of making a claim is 50% more for those that are considered unhealthy.

#### Task
The same insurance company for which I created the projection calculator tool (https://github.com/djoleary5/Actuarial_Projected_Claims) provided me with data for 100 different policyholders that includes their age, gender and health condition. Each of these policyholders have purchased the health care policy described above.

Note that health condition is provided from the insurance company as follows:
Unhealthy = 1
Healthy = 2

#### Result
Using VBA, I lopped through all of the rows to:
  -read the gender, age, and health status data
  -use that data to calcuate the projected claim amount for each year of the policy
  -populate the projection amounts for each year of the policy
I also caluated the total projected claim amount to be paid each year for all 100 policy holders and the total projected claim amount to be paid over the life of the policy for each policy holder.
