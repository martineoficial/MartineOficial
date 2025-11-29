<img src='https://images.weserv.nl/?url=github.com/martine-coding.png?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d' />

# Hi, I'm Diana Martine.

```typescript
type Dev = { name: string; role: string };
class DeveloperProfile {
  constructor(private readonly developer: Dev) {}
  getDeveloperInfo() {
    console.log(`
            Name: ${this.developer.name}
            Role: ${this.developer.role}
    `);
  }
}
const devProfile = new DeveloperProfile({
  name: "Diana Martine",
  role: "Software Engineering Analyst",
});
devProfile.getDeveloperInfo();
```

### Contact

- **Email:**  
  [martinecoding@gmail.com](mailto:martinecoding@gmail.com)
