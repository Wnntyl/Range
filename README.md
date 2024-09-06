## Example
```
using UnityEngine;

public class Example : MonoBehaviour
{
    [SerializeField] private Range<int> _range;

    private void Start()
    {
        var randomValue = Random.Range(_range.Min, _range.Max);
        Debug.Log($"A random value from the range: {randomValue}");
    }
}
```
