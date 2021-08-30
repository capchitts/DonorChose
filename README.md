# DonorChose 
DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.

How to scale current manual processes and resources to screen 500,000 projects so that they can be posted as quickly and as efficiently as possible?
How to increase the consistency of project vetting across different volunteers to improve the experience for teachers?

How to focus volunteer time on the applications that need the most assistance
The goal of the competition was to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.


It is a binary classification problem with textual data.
LSTM is used as model because of sequential nature of data and data being textual there are long dependency on words.

Conclusion:
<table>

<tr>    <th>Features</th></th> <th> Model Name </th>            <th> Model Specifications  </th>            <th>Custom AUC</th>  </tr> 
<tr> <td>Assignment 1 </td><td>Model 1</td><td>3 dense layers with ReLU activation.Adam Optimizer default learning rate. Text from Glove</td><td>0.75184745</td></tr>
<tr><td>Assignment 2</td><td>Model 2</td><td>3 dense layers with ReLU activation .Adam Optimizer default learning rate.Text with IDF</td><td>0.7592025</td></tr>
<tr><td>Assignment 3</td><td>Model 3</td><td>3 dense layers with ReLU activation .Adam Optimizer default learning rate.Text from Glove and Conv1D for other features</td><td>0.75321674</td></tr>
</table>

