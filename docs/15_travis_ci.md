## Travis.CI

* The ChefDK is fully supported.
 * example: [github.com/chef-cookbooks/mysql/blob/master/.travis.yml](https://github.com/chef-cookbooks/mysql/blob/master/.travis.yml)
* Be cautious on putting Test-Kitchen and public cloud plugins on Travis.CI, there is a possibility of being charged by public clouds.
* Another [example][tomcat] of a complete verification on the Travis system via the ChefDK.

[tomcat]: https://github.com/chef-cookbooks/tomcat/blob/master/.travis.yml
