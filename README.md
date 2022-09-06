# Martin Gardner column to book mapping project

This is the raw data for [the Martin Gardner column to book mapping project website](https://peterrowlett.net/gardner-index/).

If you know something useful about one of the articles here, please follow these instructions. If this to too technical, you can also [fill in a webform](https://forms.gle/SgZhhDYw9L5xJBUp7) or send me an email (p.rowlett@shu.ac.uk).

Instructions:

1. Log in. You may need to create a free account.
2. Go to the folder `article-data` and click to open the file for the relevant article.
3. Click the 'Edit this file' button (it's a little pencil icon top right).
4. Make changes to this file. For example, you might add a note to the `notes:` section in the following format:
    ```
    - who: "Peter Rowlett"
      when: "2 September 2022"
      note: "I have seen copies of Scientific American Sept 1969 and Mascheroni Constructions in Mathematical Circus and these match."
    ```

    If you are confident about the mapping of article to chapter, you might change `confirmed: "no"` to `confirmed: "yes"` (which will move the article from the first 'Unconfirmed' table to the second 'Confirmed' table on the website).

    Hopefully the file format is fairly clear, but don't worry if you make a mess of the syntax, I can always fix this.
5. Describe what you have done in the text field at the bottom (for example, "added note to Sept 1969") and click "Propose file change".
6. Don't panic, this won't change the live data. It will create a *pull request* which requires me to review what you have submitted and decide whether to make the change live. I might reply if I have questions.

Peter Rowlett, Sept 2022.
