Use this snippet to access the class

@Library('sl@master') _
import org.simple.Cal
node {
  t = new Cal();
  stage("first") {
  def foo = t.add(4,5)
  sh "echo ${foo}"
  }
}
