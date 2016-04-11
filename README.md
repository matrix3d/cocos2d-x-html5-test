[http://www.php.net|{{wiki:dokuwiki-128.png}}]

==== Headline Level 3 ====

=== Headline Level 4 ===

== Headline Level 5 ==

==== Headline Level 3 ====

=== Headline Level 4 ===

== Headline Level 5 ==


  * This is a list
  * The second item
    * You may have different levels
  * Another item

  - The same list but ordered
  - Another item
    - Just use indention for deeper levels
  - That's it

^ Heading 1      ^ Heading 2       ^ Heading 3          ^
| Row 1 Col 1    | Row 1 Col 2     | Row 1 Col 3        |
| Row 2 Col 1    | some colspan (note the double pipe) ||
| Row 3 Col 1    | Row 3 Col 2     | Row 3 Col 3        |

<code>
This is preformatted code all spaces are preserved: like              <-this
</code>

<code java>
package flash.__native 
{
	/**
	 * ...
	 * @author lizhi
	 */
	public class ObjectMap 
	{
		public var keys:Array = [];
		public var values:Array = [];
		public function ObjectMap() 
		{
			
		}
		
		public function get(key:Object):Object {
			return values[keys.indexOf(key)];
		}
		
		public function set(key:Object, value:Object):void {
			var i:Number = keys.indexOf(key);
			if (i ==-1) {
				i = keys.length;
				keys.push(key);
			}
			values[i] = value;
		}
		
	}

}
</code>

cocos2d-x-html5-test
====================


cocos2d x 可以用的语言
c++
lua
js

c++ 
优势，稳定 速度快
缺点，编译慢，不利于快速开发
开发工具 vs2012

lua js 属于脚本 
优点 只需编译一次c++程序，更改脚本后无需编译即可运行

cocos2dx html5（推荐） 属于 cocos2dx的一个分支。
优点 可以在浏览器中直接运行。把js代码copy到 cocos2dx的js工程里，即可在手机中运行。

开发工具推荐  idea 谷歌搜索下载


http://matrix3d.github.io/cocos2d/2013/11/16/cocos2d-test1/
