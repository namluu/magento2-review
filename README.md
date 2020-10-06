Namluu_Review module functionality is represented by the following sub-systems:
- Fixing core bug - review rating on admin form layout
    - app/code/WWG/Review/etc/adminhtml/di.xml
        - override Admin form due to protected method
    - app/code/WWG/Review/Block/Adminhtml/Edit/Form.php
        - define 2 custom Block (template only) for summary-rating and detailed-rating
        - summary-rating we add a close div </div>
        - detailed-rating we add minor style

You can see this in Marketing | User Content | All Reviews > edit a Review
