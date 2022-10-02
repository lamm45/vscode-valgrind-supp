# Syntax highlighting for Valgrind suppression files

This VS Code extension provides basic language support (i.e., syntax highlighting) for the Valgrind suppression file format.

Valgrind suppression files, often named with `.supp` extension, contain rules that tell Valgrind which problems to suppress from the output.
Suppressing output is useful, e.g., for deliberate memory leaks or for problems originating from third-party libraries.

For more information about Valgrind and its suppression file format, see
- https://valgrind.org
- https://valgrind.org/docs/manual/manual-core.html#manual-core.suppress

You may already have Valgrind suppression files in your system.
For example, Linux users may find them inside the folder `/usr/lib/valgrind/`
