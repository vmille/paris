Soixante-troisiène édition du C++ French User Group (C++Frug) Paris. Cette session sera hybride:

- eXalt nous accueillera au 10 Rue Vauvilliers, 75001 Paris, France
- Streaming sur Discord

Pour rentrer, il faudra signer le listing.

Avant de venir, vous pouvez rejoindre les serveurs Discord (https://discord.gg/tjx9bFpBfC & https://discord.gg/9aU6tZabJV). L'application Discord est plus stable que la version web.

Programme de la soirée (heure de Paris):

- 19h00 Welcome
- 19h15 News of the C++ ecosystem
- 19h20 Lightning talks
- 20h10 Snacks & drinks
- 20h40 Joel FALCOU -- From Acrobatics to Ergonomics - A Field Report on How to Make Libraries Helpful

Si vous êtes intéressé pour présenter, vous pouvez nous joindre via Discord ou MP meetup.

-------------------
Lightning talks prévus (mais venez avec les votres !)

- Polymorphisme statique versus dynamique
- C++ 2025 : le risque de l’immobilisme
- Introduction aux concepts
- Introduction aux modules

par Mouad BEN GELOUNE, développeur C++ Senior
et Florian CHARRIEAU, développeur C++ depuis plus de 10 ans, actuellement en mission à CA-CIB. En bon avocat du clean code, il aime passer du temps (souvent trop) à rendre le code plus lisible et plus maintenable.

-------------------
From Acrobatics to Ergonomics - A Field Report on How to Make Libraries Helpful
Thanks to features like concepts, C++20 promised to make template meta-programming more approachable and expressive, especially for library designers. But as we quickly learned, template programming can still be surprising or frustrating — in the worst-case scenario, it's both.

In this talk, I’ll share lessons from the past 3–4 years of building high-performance, user-friendly C++ libraries, including:

- EVE, a SIMD abstraction layer designed for performance and portability.
- KUMI, a re-imagined tuple library with algorithmic support.
- KIWAKU, a toolkit for multi-dimensional arrays that aims to be efficient and ergonomic.

We’ll explore the practical challenges of designing ergonomic C++ APIs:

- Error messages that make sense: `static_assert` or concepts? How to avoid large template error stacks? ...
- APIs that align with user intuition: How do we provide options on the functions' semantics? How to design meaningful extension points, ...
- How bold design decisions can pay off: going sideways with standard practices, turning CTAD upside-down, ...

We'll discuss how C++20 features helped us reduce friction and increase clarity once we use them properly.
If you’ve ever screamed into the void over template errors, please join in!

Joel FALCOU
is an associate professor at the University Paris-Saclay and Researcher at the LISN - the Laboratoire Interdisciplinaire des Sciences du Numériques - in Orsay, France. His research focuses on studying generative programming idioms and techniques to design tools for parallel software development. And for some reasons, he does all of that in C++.
The main parts of his work are:

- the exploration of Embedded Domain Specific Language design for parallel computing on various architectures;
- the definition of a formal framework for reasoning about meta-programs.

Joel is the co-host of the C++FRUG Meetup, president of the C++FRUG Association, co-organizes the CPPP Conference, and is part entrepreneur, being one of the co-founder of CODE RECKONS, a company focused on bringing people and company up to date to the best and newest C++.