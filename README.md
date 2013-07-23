# NAME

Dist::Zilla::Plugin::MakeMaker::IncShareDir - MakeMaker subclass that bundles File::ShareDir::Install in inc/

# SYNOPSIS

    use Dist::Zilla::Plugin::MakeMaker::IncShareDir;

# DESCRIPTION

Dist::Zilla::Plugin::MakeMaker::IncShareDir is a plugin to emit `Makefile.PL` but
bundles [File::ShareDir::Install](http://search.cpan.org/perldoc?File::ShareDir::Install) in `inc`.

You probaly don't need to use this plugin. This plugin is made
specifically for [App::cpanminus](http://search.cpan.org/perldoc?App::cpanminus) where the build files can't have
external dependencies due to bootstrapping reasons.

# AUTHOR

Tatsuhiko Miyagawa <miyagawa@bulknews.net>

# COPYRIGHT

Copyright 2013- Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Dist::Zilla::Plugin::MakeMaker](http://search.cpan.org/perldoc?Dist::Zilla::Plugin::MakeMaker) [Dist::Zilla::Role::ModuleIncluder](http://search.cpan.org/perldoc?Dist::Zilla::Role::ModuleIncluder)
