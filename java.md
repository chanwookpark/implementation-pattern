
# JavaDoc

(JavaDoc Reference )[http://docs.oracle.com/javase/7/docs/technotes/tools/windows/javadoc.html#since]

# Log

로깅은 slf4j를 사용한다.

## 로거 선언

'''java
import org.slf4j.Logger;
import org.slf4j.LoggerFactory;

private final Logger logger = LoggerFactory.getLogger(Xxxx.class);
'''
