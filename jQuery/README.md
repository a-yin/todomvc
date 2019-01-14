# TodoMVC

#### 任务清单，这里以jQuery 为例，无非CRUD常规操作

- Create（添加todo记录）

  直接在**What needs to be done？** 输入框添加新的todo记录，并回车

- Retrieve（查询todo记录）

  根据**All、Active、Completed** 三种不同状态显示对应的todo记录

  - All：显示所有状态下的todo记录（包括Active和Comleted），按创建时间升序显示，最新创建的显示在最下面
  - Active：显示所有还没完成的列表项
  - Completed：显示所有已完成的列表项

- Update（更新todo记录）

  - 单条记录
    - 更新记录状态：在todo记录最前面的圈单击打钩，会改变todo记录的字体颜色和划线，并添加到Active状态的列表
    - 更新记录内容：**Double-click to edit a todo**  双击可进行todo项的内容修改
  - 多条记录
    - 在输入框最左侧，点击字体图标，可使所有的todo记录变成Completed状态，并添加到Completed状态的列表

- Delete（删除todo记录）

  - 单条记录

    - 点击单个记录项最后的小×进行删除

  - 多条记录

    - 点击右下角的**Clear completed**

    注：只有当有todo记录处于Completed状态时，右下角才会出现**Clear completed**的button


------



除此之外，还有提供了其它功能

1. 左下角统计Active状态下todo记录的数量

2. 即使关了浏览器，todomvc还是保存todo记录列表
