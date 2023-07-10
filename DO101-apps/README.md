# DO101-apps

Apps for the DO101 course.

```
http http://$(oc get route/version --no-headers=true | awk '{ print $2 }')
```