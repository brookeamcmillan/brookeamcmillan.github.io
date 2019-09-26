### Language Features: Observer Pattern

The observer pattern in java is referred to as the publish-subscribe pattern.  It's defined as too many dependencies between objects. So when one (dependents) object changes the others are updated.  
```markdown
(https://miro.medium.com/max/1203/0*3KbyEbfuH8S3NY6A)
```

In the link above it shows the observer pattern.
The pattern has four roles:
1) Subject- It informs the objects of change (abstract class)

2) Concrete Subject- When the class makes a change it will inform the observers.

3) Observer- Defines an updated method (abstract class)

4) Concrete Observer- It updates it's upon getting new information
