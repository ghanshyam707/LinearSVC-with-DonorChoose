# LinearSVC-with-DonorChoose
Applied LinearSVC on Donorchoose dataset

Created 4 dataset. Each dataset contains text features encoded with different encoding techniques.<br>
**Set1** | Text features encoded with simple `Bag of words` vectorizer.<br>
**Set2** | Text Features encoded with `TFIDF` vectorizer.<br>
**Set3** | Text features encoded with `Avarage Word2Vec` vectorizer.<br>
**Set4** | Text features encoded with `TFIDF Word2Vec` vectorizer.<br>

Then SVC is applied on all 4 datasets with L1 and L2 penalty.<br>

<b> Conclusion after applying LR to all datasets </b><br>

`SVC` have very low `recall` value with all the datasets. Not able to separate Positive points from negative points.<br>
This might be because `SVM` not able to converge to global minima on loss function because of slow convergance.<br>
`RBF` kernel might work well on this dataset but cannot be applied because of large number of data points.<br>

##### Credits : www.AppliedAICourse.com
