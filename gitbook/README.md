# multi code tab

{% tabs %}
{% tab title="_c.py" %}
```python

class Solution:
    def rob(self, nums):
        first = second = 0

        for val in nums:
            first, second = second, max(second, val + first)

        return second

```
{% endtab %}

{% tab title="_c.java" %}
```java

// c.java
// more better version

class Solution {
	public int rob(int[] nums) {
		int first = 0;
		int second = 0;
		int temp;

		for (int val : nums) {
			temp = first;
			first = second;
			second = Math.max(second, val + temp);
		}

		return second;
	}
}


```
{% endtab %}

{% tab title="Untitled" %}
asdfasdfasdf

as

df

asdf

a

sdf

a

sdf
{% endtab %}
{% endtabs %}

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td></tr></tbody></table>

$$
f(x) = x * e^{2 pi i \xi x}
$$

{% embed url="https://www.youtube.com/watch?ab_channel=RickAstley&v=dQw4w9WgXcQ" %}

{% embed url="https://www.youtube.com/shorts/cqVQ8Vbw1JI" %}

{% embed url="https://gist.github.com/withrvr/280c070398d42fe007c1510bd771ef8d" %}

{% swagger method="get" path="" baseUrl="" summary="" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}

<img src=".gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

```
// Some code
```

<figure><img src=".gitbook/assets/1128-191-linkedin-banner.png" alt=""><figcaption><p>asdfasdfasd</p></figcaption></figure>

<figure><img src="https://images.unsplash.com/photo-1674856320411-8c63716007d6?crop=entropy&#x26;cs=tinysrgb&#x26;fm=jpg&#x26;ixid=MnwxOTcwMjR8MHwxfHJhbmRvbXx8fHx8fHx8fDE2NzY0MDE2NjI&#x26;ixlib=rb-4.0.3&#x26;q=80" alt=""><figcaption></figcaption></figure>

{% file src=".gitbook/assets/Developer_Guide.md" %}

<details>

<summary>asdfasdf</summary>



</details>

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

{% code title="b.java" overflow="wrap" %}
```java

// POV: as nums
// Math.max(nums[1], nums[2] + nums[0])

class Solution {
	public int rob(int[] nums) {
		if (nums.length == 1)
			return nums[0];

		nums[1] = Math.max(nums[0], nums[1]);

		for (int i = 2; i < nums.length; i++)
			nums[i] = Math.max(nums[i - 1], nums[i] + nums[i - 2]);

		return nums[nums.length - 1];
	}
}

```
{% endcode %}

{% embed url="https://codepen.io/withrvr/pen/MWBLoPd" %}
testing
{% endembed %}

<details>

<summary></summary>



</details>

```cpp
// Some code

int a = 1;

int b = 2;


int c = a+b;tab
```
