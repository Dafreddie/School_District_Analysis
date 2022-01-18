

# School District Analysis

### Overview: 
Maria the chief data scientist of a city school district was tasked with preparing all standardized test data for analysis, recording, and presentation to give insights
to inform discussions and strategic decisions at the school and district level. I was tasked to aggregate data to showcase trends in school performance
to aid the school board in decisions regarding school budgets and priorities. I was given data referring to math and reading test scores and the schools that it was proctored from 
for aid in my analysis. 

### Results:

#### District Summary:
>![District Summary](https://user-images.githubusercontent.com/95380144/149857511-362bba99-f078-4a36-a618-93a5796c55b4.png)

#### School Summery:
>![School Summery](https://user-images.githubusercontent.com/95380144/149857730-4f8ddcbb-f21e-4649-9094-614374dde5cc.png)

There would be no correlation from changing the scores of Thomas High Schools 9th grade to NaN in relation to the other grades of that school since we are not filling that void with any other value. If we changed it a 0 or to another numerical value then it would of still not have effected the other grades at this stage in the analysis. 

#### Thomas High School By Grade (Math):
>![Math Grade Score](https://user-images.githubusercontent.com/95380144/149860126-68f7cc0d-f00a-42dc-a19d-a1700e13dba0.png)

#### Thomas High School By Grade (Reading):
>![Reading Grade Score](https://user-images.githubusercontent.com/95380144/149860138-c687b949-9e74-49e0-93cb-e03b5a956d46.png)

There is now a NaN in the place of Thomas High Schools 9th grade scores that was previously filled with the grades score from the academic dishonest dataset. All other scores in the grades were not effected by the change in the data. 

#### Scores By School Spending:
>![School Spending on Scores](https://user-images.githubusercontent.com/95380144/149860794-c82b319b-c821-4bd7-a7bc-c94707d928a1.png)

There was not any noticeable changes in the school spending based on the scores either. After I balanced the bins into which I placed all of the data into I noticed that there was no immediate change. But if I didn’t balance the bins then the school scores would of showed NaN for any range between 0-500.

#### Scores By School Size:
>![School Size Scores](https://user-images.githubusercontent.com/95380144/149860825-d272356f-071d-4fda-80be-1562072d9ddb.png)

There was no alterations in the scores for the school size either. There is also a close relation to all of the data otherwise showing that larger schools were more inclined to have lower test scores then those of the medium or smaller schools. Other all data is practically the same.

#### Scores By School Type:
>![School Type Scores](https://user-images.githubusercontent.com/95380144/149860926-57e8239f-5858-4e3c-b448-407e27d61497.png)

There is no differences between the altered data frames compared to the original with the corrupt data. There is evidence that charter schools do better in both data sets which can be proven by looking at the percentage of overall passing grades from Charter schools to District schools. Otherwise all data is equal in both data frames.

#### Summery:
There wasn’t a huge change nor loss in integrity of the data by swapping out the test scores of Thomas High School 9th graders with NaN due to academic dishonesty. There were changes in the scores pertaining to Thomas High School and they follow as such:
1. The percentage of students who passed math dropped from 93.2% to 66.9%
2. The percentage of students who passed reading dropped from 97.3% to 69.7%
3. The overall passing percentage dropped from 90.9% to 65.1%
4. Thomas High School also dropped out of the top 5 ranking list of high schools in the district
