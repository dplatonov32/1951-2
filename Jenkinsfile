//     def lib = library identifier: 'folder@snapshot', retriever: legacySCM(scm)
    @Library('folder')
    import src.pkg.Clazz
    greet(new Clazz().whereAmI())
// if (env.CHANGE_FORK == null) {
//   def lib = library identifier: 'global@snapshot', retriever: legacySCM(scm)
//   greet(lib.pkg.Clazz.whereAmI())
// } else {
//   unstable 'Library changes may only be tested using origin branches by contributors with write access'
// }
