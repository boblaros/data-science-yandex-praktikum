# Comment Moderation Model

**Client**: Wikishop Online Store

**Context**: Wikishop is launching a new feature where users can edit and enhance product descriptions similar to wiki communities. Users will propose edits and comment on changes made by others. The store needs a tool to identify toxic comments and send them for moderation.

**Project Goal**: Train a model to classify comments as `positive` or `negative` with an F1 score of at least 0.75.


## Conclusion

We worked with 159,292 unique comments, with ~10% toxic and ~90% non-toxic. Three models were trained: `LogisticRegression`, `PassiveAggressiveClassifier`, and `LGBMClassifier`. The `PassiveAggressiveClassifier` performed best with an F1 score of 0.78 during cross-validation and 0.79 on the test set.