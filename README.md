# Brain Networks Hackathon

## Getting started

### Softwares and toolboxes

### Open access datasets

## Contribute

### Website

To build the website locally, you first need to install [Jekyll](https://jekyllrb.com/). Then, you can launch in two terminal windows, from the repository folder, the following commands:

```sh
sass --watch docs/assets/sass/:docs/assets/css/
```

to build the `css` style sheets, and,

```sh
jekyll serve --source docs/
```

to start a Jekyll server.

You should now be able to access the website at the following address: http://127.0.0.1:4000.

## Hosting

### Namecheap

Namecheap was the DNS server used in 2019. The following host records were entered: (These are the only host records in the list under Advanced DNS section)

```sh
A Record  @   185.199.108.153
A Record  @   185.199.109.153
A Record  @   185.199.110.153
A Record  @   185.199.111.153
CNAME     www brain-network.github.io
```

### Github pages

Ensure the domain name is correct in the github-pages section in settings.
