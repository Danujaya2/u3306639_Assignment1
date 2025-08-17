# Step 4 – Word Code (Pseudocode)

This folder contains the **pseudocode implementation** for the automated pet feeder.  

### Contents
- Word code describing the logic step by step.
- Comments for clarity and explanation.

### Example
```plaintext
BEGIN
  SET feeding_times
  LOOP forever
    IF current_time == feeding_time THEN
        DISPENSE food
        CHECK portion size
        IF bin is empty THEN
            DISPLAY "Refill needed"
        ENDIF
    ENDIF
  END LOOP
END
