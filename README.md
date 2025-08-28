# overview

## updated as of 2025-08-28
- those handshake DNS are too unstable, giving them up, and went back to a static page with JAMstack ;
- using lume this time, both gatsby and fresh are too heavy ; 
- based on : [lume, with the theme simple-wiki][link-01]
- custom domain : `wiki.dallmo.com`
  - with redirection from `dallmo.com`
  - which is in turn a simple http redirect app hosted in [deno deploy][link-02] ;
    - [the deno project][link-03], where dallmo.com records in route53 are associated to ; 
    - [the github repo][link-04], a simple http server ; 

## updated as of 2025-05-31
- gitHub pages for the github account dallmo
- temp parking index, handshake domain check, hosting on root, as of 2025-05-31-a.
  - handshake TLD : dallmo
  - domain for this page : info.dallmo

## updated as of 2024-01-04
- github pages for dallmo.com ; 
- built with gatsby, it loads fast when published, but kind of heavy when building / dev time, too much dependencies even for a minimal project ; 
- preferred the `Fresh` version deployed on deno.dev instead : https://dallmo.deno.dev ;


[link-01]: https://lume.land/theme/simple-wiki/
[link-02]: https://deno.dev
[link-03]: https://dash.deno.com/projects/dallmo/
[link-04]: https://github.com/dallmo/deno-http-redirect
