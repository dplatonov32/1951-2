    def lib = library identifier: 'folder@snapshot', retriever: modernSCM(
  [$class: 'GitSCMSource',
   remote: 'https://github.com/Pldi23/1951-library.git',
   credentialsId: 'pldi23'])
    greet(lib.pkg.Clazz.whereAmI())
// if (env.CHANGE_FORK == null) {
//   def lib = library identifier: 'global@snapshot', retriever: legacySCM(scm)
//   greet(lib.pkg.Clazz.whereAmI())
// } else {
//   unstable 'Library changes may only be tested using origin branches by contributors with write access'
// }
