// def lib = library identifier: 'library-test@master', retriever: legacySCM(scm);
node() {
    def lib = libraryFromLocalRepo()
    lib.hello()
}

def libraryFromLocalRepo() {
    library(identifier: 'library-test@snapshot', retriever: legacySCM(scm))
}