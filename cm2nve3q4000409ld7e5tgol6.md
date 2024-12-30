---
title: "Exploring the Synergy: Python Meets Rust at the 2024 Conference"
datePublished: Thu Oct 24 2024 22:23:42 GMT+0000 (Coordinated Universal Time)
cuid: cm2nve3q4000409ld7e5tgol6
slug: rust-x-python-conference
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1733608223148/b72e037e-526c-4d4c-b9fc-77bfc49d4157.webp
tags: python, rust, data-validation, python-x-rust-conference-2024

---

As a newcomer to Rust, I attended my first Python x Rust conference on October 22, 2024, with an open mind. Although I had been aware of the buzz surrounding Rust for a few years, I felt more *comfortable* with Python, which had served me well. However, the collaborative nature of this event encouraged me to finally take the plunge and explore Rust.

We started with a talk by David Seddon. He discussed various topics - which I am admittedly a novice to such as py03, maturin and more. The part that stood out to me is when he spoke about the time difference when loaded data in Python versus Rust+Python.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1729793096844/f4c341fa-afe4-47d4-a171-5246fde4721a.png align="center")

Rust x Python had more than 6x improved performance on sample data when compared against code written in only python. This was eye-opening. I was ready to learn more. David then went to explain the differences between python data types and rust data types.

What drew me to python initially was it’s ‘ease of use’ and the number of python libraries that makes you spend more time quickly spinning ideas - unlike other languages like C++ where more time will be spent pondering about memory allocation (lol).

I understand what could be seen as a positive in python can also be deemed a negative. i.e. Python makes is ‘easy’ as it does not explicitly specify the variable's data type. In the short term, this makes programming I guess ‘easy’. Working in the real world however, I am acutely aware that issues such as poor memory management and garbage collection when working on tasks plus variables that can change during the program may introduce errors.

The next talk by David Hewitt was great and continued the discussion on Py03 and Maturin... Again, many topics were very new to me so I will need to go over this again to understand…. The main takeaways were 1) Rust code is ‘just’ an import 2) Python function calls end up executing rust code in a few steps. 3) Py03 handles all the complexity so you don’t have to.

Lastly, Samuel Colvin spoke about Pydantic and Rust. The title was “Why and how Pydantic uses Rust”. I learnt that Pydantic performs data validation and more and has a growing user base with 280M downloads per month. And Samuel is the developer of the Pydantic API! He mentioned that Pydantic V2 had a complete rewrite where the base was rewritten in Rust. Pydantic V2 is 5 - 50x faster than Pydantic V1.

He spoke about the advantages of rust such as performance, reuse of rust libraries, explicit error handling, the notion of rust being easier to maintain because of the compliers handling of errors and more. The disadvantages include it’s apparently slower to develop, and as it’s a less popular language there is less support from a community unlike python. Also, developers have to distribute binaries or leave users to compile it.

Possibly because of the explicit type handling? and requires the developer to consciously trace their errors instead of dumping all errors in python and waiting for the error message - i.e. requires more attention on the developers end?.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1729807972089/3bf668e3-45e8-4f59-ac68-d6e171215251.png align="center")

Overall my main takeaways is that at XXmillion users and XX downloads, python is a popular program language that is easy to read and easy for developers to get up to speed with the core concepts of programming ‘fast’. However for professional developers, the new language on the block rust attempts to solve the critical issues that professional developers have. Such as issues caused by the way python automatically reads variables data types. So this reduces the risk of errors, if the programmer is able to ensure they can declare their types properly.

The main advantage of Rust for me is the performance improvements. For instance 6x faster when using rust with python, and 5-50x improved performance with Pydantic’s API.

Attending the Python x Rust conference was an enlightening experience that opened my eyes to the potential of combining these two powerful programming languages. While Python's ease of use and extensive library support make it a favorite among developers, Rust offers significant performance improvements and robust error handling, which are crucial for professional development. The talks by David Seddon, David Hewitt, and Samuel Colvin highlighted the synergy between Python and Rust, showcasing how Rust can enhance Python applications, particularly in terms of speed and reliability. The integration of Rust in tools like Pydantic demonstrates the practical benefits of this collaboration, offering substantial performance gains. As I continue to explore Rust, I am excited about the possibilities it brings to the table, especially in optimizing Python applications for real-world challenges. This conference has inspired me to delve deeper into Rust, embracing its strengths to complement my Python skills.

Starting the day knowing nothing about Rust, the real question is `red` or `blue` 👾.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1733608071656/3c4396f2-76b2-4b8a-8e7c-3c080d1981c0.png align="center")