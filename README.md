# SpringSecurityWithAnnotation

Spring的 @PreAuthorize/@PostAuthorize 注解更适合方法级的安全，也支持Spring 表达式语言，提供了基于表达式的访问控制。

@PreAuthorize 注解适合进入方法前的权限验证，@PreAuthorize可以将登录用户的roles/permissions参数传到方法中。

@PostAuthorize 注解使用并不多，在方法执行后再进行权限验证。 

所以它适合验证带有返回值的权限。Spring EL 提供 返回对象能够在表达式语言中获取返回的对象returnObject。
