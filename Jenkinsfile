if (env.CHANGE_FORK == null) {
  def lib = library identifier: 'global@master'
  greet(lib.pkg.Clazz.whereAmI())
} else {
  unstable 'Library changes may only be tested using origin branches by contributors with write access'
}
