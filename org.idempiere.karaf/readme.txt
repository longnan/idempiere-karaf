1. add into build process in Parent POM
2. copy all generated folder from target/assembly into root of idempiere-server
3. run bin/karaf.bat
4. feature:install -v org.idempiere.karaf.*


## Tips
Search bundle package

package:exports | grep xxx

capabilities 0 | grep osgi.ee