[![Cpan license](https://img.shields.io/cpan/l/Acme-CPANAuthors-Malaysian.svg)](https://metacpan.org/release/Acme-CPANAuthors-Malaysian)
[![Cpan version](https://img.shields.io/cpan/v/Acme-CPANAuthors-Malaysian.svg)](https://metacpan.org/release/Acme-CPANAuthors-Malaysian)

# NAME

Acme::CPANAuthors::Malaysian - We are Malaysian CPAN authors (Kami para penulis
CPAN Malaysia).

# SYNOPSIS

    use Acme::CPANAuthors;
    use Acme::CPANAuthors::Malaysian;

    my $authors = Acme::CPANAuthors->new('Malaysian');

    my $number   = $authors->count;
    my @ids      = $authors->id;
    my @distros  = $authors->distributions('KIANMENG');
    my $url      = $authors->avatar_url('KIANMENG');
    my $kwalitee = $authors->kwalitee('KIANMENG');

# DESCRIPTION

This module provides a list of Malaysian CPAN author's Pause ID mapped to name
for [Acme::CPANAuthors](https://metacpan.org/pod/Acme::CPANAuthors).

# MAINTENANCE

Send email, open a ticket, or make a pull request to add your own Pause ID and
name.

# REPOSITORY

Source repository at [https://github.com/kianmeng/acme-cpanauthors-malaysian](https://github.com/kianmeng/acme-cpanauthors-malaysian).

How to contribute? Follow through the [CONTRIBUTING.md](https://github.com/kianmeng/acme-cpanauthors-malaysian/blob/master/CONTRIBUTING.md) document to setup your development environment.

# AUTHOR

Kian Meng, Ang <kianmeng@cpan.org>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2019- Kian Meng, Ang.

This is free software, licensed under:

    The Artistic License 2.0 (GPL Compatible)

# SEE ALSO

[Acme::CPANAuthors](https://metacpan.org/pod/Acme::CPANAuthors) - The parent module that handles all.

[Acme::CPANAuthors::Indonesian](https://metacpan.org/pod/Acme::CPANAuthors::Indonesian) - Our neighbouring country.
