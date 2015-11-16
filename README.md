### Query crap

A repo full of crap about queries

# What is this for?
We're gonna store some SPARQL queries here. Each of them in a different file.
Then we're gonna pay attention to push events via webhooks. In another endpoint,
we'll filter commited files with the `.rq` extension to distinguish modified
SPARQL queries. Then we'll retrieve those.

For each new query, we'll add a new route using a template.
For a modified query, we'll re-render the template with the new query.
