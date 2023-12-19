# Best practice for collaboration

## A basic feature branch strategy

A basic way to collaborate on a common repository is to use *feature branching*.
A *feature* in this context is any piece of work that adds to of the
software's overall development, whether this be a new piece of functionality, a
bug fix, some documentation, etc. In feature branching, new features are
developed in their own, dedicated *feature branches* that branch off the
`main` branch. When the feature is ready to be shared with others, the feature
branch is merged back into `main`.