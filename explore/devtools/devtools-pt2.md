1. The bug was that the input numbers were actually strings, so the + operator concatenated them instead of adding.
2. Fix by converting inputs to numbers before adding