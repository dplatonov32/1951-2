// def lib = library identifier: 'library-test@master', retriever: legacySCM(scm);
node() {
    def lib = libraryFromLocalRepo().vars.hello
    lib.call()
}

def libraryFromLocalRepo() {
    // Workaround for loading the current repo as shared build lib.
    // Checks out to workspace local folder named like the identifier.
    // We have to pass an identifier with version (which is ignored). Otherwise the build fails.
    library(identifier: 'library-test@snapshot', retriever: legacySCM(scm))
}