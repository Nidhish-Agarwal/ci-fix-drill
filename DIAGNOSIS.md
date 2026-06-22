### Failure 1 - Test Failure

Step: Run unit tests  
Error: Expected: 90, Received: 100  
Cause: Function not applying discount OR wrong test expectation

### Failure 2 - Dependency Failure

Step: Install dependencies  
Error: npm ERR! lockfile mismatch  
Cause: package.json and package-lock.json not in sync

### Failure 3 - Workflow Failure

Step: Test job skipped  
Error: missing `needs:`  
Cause: test runs before install
