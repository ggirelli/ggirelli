<!-- markdownlint-disable MD033 MD041 -->

<h2 align="center">
 👋 Hi there! You can call me "GG" 😉
</h2>

<p align="center">
  <a style="border-radius: 50%;" href="https://genomic.social/@ggirelli" target="_blank" title="GirelliGabriele">🐘 Mastodon</a> |
  <a style="border-radius: 50%;" href="https://www.linkedin.com/in/ggirelli" target="_blank" title="ggirelli">👔 LinkedIn</a> |
  <a style="border-radius: 50%;" href="https://www.instagram.com/ggirelli" target="_blank" title="ggirelli">🎨 Instagram</a> |
  <a style="border-radius: 50%;" href="https://scholar.google.se/citations?user=doYZ7JgAAAAJ" target="_blank" title="Google Scholar">🎓 Publications</a> |
  <a style="border-radius: 50%;" href="https://ggirelli.info/blog/" target="_blank" title="Filopoe">🚀 Blog</a>
</p>

<p>
  <small>
    To leave feedback, visit the <code>issues</code> tab of the repository you are interested in!<br/>
    If that is not possible, send an email to <code>issue at ggirelli dot info</code>.<br/>
    If a repository is archived, that means I do not support it anymore.
  </small>
</p>

You can find more ways to get in touch on my virtual [business card]!

Here are some stats:

![](https://github-readme-stats.vercel.app/api?username=ggirelli&theme=dark&hide_border=false&include_all_commits=True&count_private=True)
![](https://nirzak-streak-stats.vercel.app/?user=ggirelli&theme=dark&hide_border=false)

And a short story:
```python
from gg.enums import Pronoun
from gg.types.education import EdLevel, Institute, Subject
from gg.types.geography import City, Country, Province
from gg.types.personal import Url
from gg.types.time import FromYear, ToYear
from gg.types.work import Employer, JobTitle


class ItsMeGG:
    """Some info on myself."""
    pronouns: tuple[Pronoun, ...] = (Pronoun.HE, Pronoun.HIM)
    indie_website: Url = "https://ggirelli.info"
    spirit_animal: str = "Caffeinated squirrel ☕🐿️"
    hometown: tuple[City, Province, Country] = (
        "Bussolengo",
        "Verona",
        "Italia",
    )

    # Work and Ed
    education: tuple[
        tuple[FromYear, ToYear, EdLevel, Subject, Institute, Country], ...
    ] = (
        (2009, 2012, "BS", "Biotechnology", "Università di Trento", "Italia"),
        (2012, 2014, "MS", "Biotechnology", "Università di Trento", "Italia"),
        (2016, 2021, "PhD", "Bioinformatics", "Karolinska Institute", "Sweden"),
    )
    jobs: tuple[tuple[FromYear, ToYear, Employer, JobTitle]] = (
        (2022, 2025, "10X Genomics Sweden AB", "Sr. Computational Biologist"),
    )
    code: tuple[str, ...] = ("Python", "R", "Rust", "Go")
    tools_and_tech: tuple[str, ...] = (
        "bazel",
        "protobuf",
        "uv",
        "GitHub Actions",
    )
    ask_me_about: tuple[str, ...] = (
        "Genome architecture",
        "good coding practices",
        "spatial transcriptomics.",
    )

    # Free time and misc.
    hobbies: tuple[str, ...] = ("sketching", "reading", "cooking", "blogging")
    current_focus: str = (
        "Having fun with an old film camera from the early 60s!"
    )
    fun_fact: str = "I am hypophantasic, but enjoy drawing!✏️"
```

[business card]: https://ggirelli.info
