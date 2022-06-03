interpreter:
	javac \
		com/craftinginterpreters/lox/Lox.java \
		com/craftinginterpreters/lox/Scanner.java \
		com/craftinginterpreters/lox/Token.java \
		com/craftinginterpreters/lox/Expr.java \
		com/craftinginterpreters/lox/Parser.java \
		com/craftinginterpreters/lox/Interpreter.java \
		com/craftinginterpreters/lox/RuntimeError.java \
		com/craftinginterpreters/lox/TokenType.java

run_interpreter:
	java \
		com.craftinginterpreters.lox.Lox

generate_ast:
	javac \
		com/craftinginterpreters/tool/GenerateAst.java

run_generate_ast:
	java \
		com.craftinginterpreters.tool.GenerateAst \
		com/craftinginterpreters/lox/

ast_printer:
	javac \
		com/craftinginterpreters/lox/AstPrinter.java

run_ast_printer:
	java \
		com/craftinginterpreters/lox/AstPrinter

