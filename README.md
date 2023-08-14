    1、既然选择远方，当不负青春，砥砺前行。

    2、青春由磨砺而出彩，人生因奋斗而升华！

def fibonacci(n)
  return n if ( 0..1 ).include? n
  (fibonacci(n - 1) + fibonacci(n - 2)) #recursive calls
end