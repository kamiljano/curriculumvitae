# Curriculum Vitae

You can view my current CV [here](https://github.com/kamiljano/curriculumvitae/blob/master/Kamil%20Janowski%20-%20Curriculum%20Vitae.pdf)
Or an [online version](http://resume.kgjanowski.com)

# Deployment

```
aws s3 sync --acl public-read --sse --delete ./ s3://www.kgjanowski.com
```