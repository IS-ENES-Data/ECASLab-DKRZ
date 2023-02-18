# ECAS: Getting started

Analysing climate model data hosted in PetaByte scale data archives is intricate. 
Specific data center side services are needed to avoid data downloads and support data near processing.
Three major components of the ECAS installation at DKRZ are introduced in the following:
- a **jupyter hub environment** with direct access to the data collections
- **specific data catalogus** supporting the discovery and access of the data collections and
- **data center side web services** exposing oftenly needed data (pre-)processing capabilities


## ECAS jupyter hub environment at DKRZ

- The jupyter hub installation at DKRZ is accessible via juypterhub.dkrz.de 
- you need first to register first at http://lub.dkrz.de 
- after this log into luv.dkrz.de to request access to the project providing the ECAS service - it is called `` 1088-CMIP data analysis ``
- documentation on using the juypterhub at dkrz is available at:
   - a
   - b
   - c 

For more about MyST, see [the MyST Markdown Overview](https://jupyterbook.org/content/myst.html).

```{note}
The jupyter hub environment provides limited processing ressources on a best effort basis. 
Ressource usage is monitored and in case you need larger CPU/storage allocations please contact data_pool@dkrz.de
```

## ECAS intake catalog support 

Roles and directives are two of the most powerful tools in Jupyter Book. They
are kind of like functions, but written in a markup language. They both
serve a similar purpose, but **roles are written in one line**, whereas
**directives span many lines**. They both accept different kinds of inputs,
and what they do with those inputs depends on the specific role or directive
that is being called.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`notebooks`.


## ECAS Web Processing Services

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
