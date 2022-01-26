if (env.CHANGE_FORK == null) {
  def lib = library identifier: 'global@snapshot', retriever: legacySCM(scm)
} else {
  unstable 'Library changes may only be tested using origin branches by contributors with write access'
}
greet(lib.pkg.Clazz.whereAmI())
